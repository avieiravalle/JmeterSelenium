1 Abrir o Jmeter.
2 Baixar pesquisar por webdriver plugin Jmeter
3 Adcionar usu�rios 
4 Adcionar elementos de configura��o -> configuar webdriver
5 Adcionar webdriver sampler
6 Adicionar Ouvintes Arvore ou tabelas.
7 incrementar codigo JAVA como no exemplo.
8 Rodar testes.


WDS.sampleResult.sampleStart()
WDS.browser.get("https://www.google.com/");
var SearchBox = WDS.browser.findElement(org.openqa.selenium.By.name("q"))
SearchBox.sendKeys("Automa��o de teste");
SearchBox.sendKeys(org.openqa.selenium.Keys.ENTER);

//WDS.browser.findElement(org.openqa.selenium.By.name("q")).clear();
//WDS.browser.findElement(org.openqa.selenium.By.name("q")).sendKeys("teste");
//WDS.browser.findElement(org.openqa.selenium.By.name("q")).sendKeys(Keys.ENTER);

WDS.sampleResult.sampleEnd()
