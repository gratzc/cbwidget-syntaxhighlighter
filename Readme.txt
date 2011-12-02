A Widget to use that uses the SyntaxHighlighter project to format your code
SyntaxHighlighter URL: http://alexgorbatchev.com/SyntaxHighlighter/
Credit to Tony Garcia as this is mainly based off the Mango Plugin he wrote
Tony Garcia Mango Plugin URL: https://github.com/tony-garcia/SyntaxHighlighter-Mango-Plugin
	ContentBox setting:
		shLanguages - comma delimited list of languages you want available, defaults to "AS3,ColdFusion,Java,JScript,Plain,Sql,Xml"
		shTheme - Theme css file to use for highlighting, defaults to "shThemeDefault.css"
	Usage:

	Call the widget and pass it the text you want to format

	#cb.widget('SyntaxHighlighter',{content=prc.entry.getContent()})#

	You designate which language to highlight by using an alias for the language in the opening code tag after a colon. For example,
	the alias for ColdFusion code highlighting is "cf":

	[code:cf]
	<cfset message = "This plugin is really cool!!!" />
	<cfoutput>#message#</cfoutput>
	[/code]

	Here is a list of aliases for all code brushes included in the plugin (also, make sure the brushes you want to use are
	selected in the plugin configuration --see above):

	as3  (ActionScript3)
	bash (Bash)
	cf   (ColdFusion)
	cpp  (C++)
	csharp   (C#)
	css  (CSS)
	delph  (Delphi)
	diff  (Diff, Pascal)
	erlang (Erlang)
	groovy (Groovy)
	java  (Java)
	javafx  (JavaFX)
	js   (JavaScript, JScript)
	perl  (Perl)
	php  (PHP)
	ps  (PowerShell)
	python (Python)
	ruby  (Ruby)
	scala  (Scala)
	sql   (SQL)
	text  (Text)
	vb  (VB, VB.NET)
	xml (XML, XHTML, HTML)