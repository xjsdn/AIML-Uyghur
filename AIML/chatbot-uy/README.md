# chatbot-utf8

chatbot for languages have to support utf8 

you can use https://github.com/kompasim/AIML-Uyghur to customize for Uyghur language

it is bases on https://github.com/pe77/Program-P and AIML 2.5

![chatbot](/images/demo.png)

> the pattern rule :

```PHP
		$pattern = str_replace(' * ', ' (.+) ', $pattern);
		$pattern = str_replace('* ', '(.+) ', $pattern);
		$pattern = str_replace(' *', ' (.+)', $pattern);
		$pattern = str_replace('*', '(.+)', $pattern);
		$pattern = str_replace(' # ', '[ ]*(.*) ', $pattern);
		$pattern = str_replace(' #', '[ ]*(.*)', $pattern);
		$pattern = str_replace('# ', '(.*)[ ]*', $pattern);
		$pattern = str_replace('#', '(.*)', $pattern);
```