# ddm-parsing
This a module developed for parsing Liferay's Journal Article ddm element and fetching document library from the DDM field and converting it into HTML. the HTML is parsed through using JSoup Library and added to Liferay's Web content. 

The inspiration behind developing this plugin was from a customer requirement where they wanted to develop a web content type and allow uploading research paper documents (only PDFs) and then extract the information from it and render within the same web-content. As per customer,Most of the offline utilities provide the complete DOM conversion incompatible to our Web content , I tried using a combination of Apacha tika (for conversion to DOM) and JSOUP for formatting to a structure compatible to our webcontent.
