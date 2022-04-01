# Pseudocode of URL Shortener Design
由於Node.js語法經驗不多，因此以演算法形式表達個人思考邏輯，盼能藉此讓貴公司了解本人充滿熱忱的心意。

此專案檔案還含有HTTP Server之建置。

# create shorten URL
input origin URL

if(origin URL in database)

{

  output the shorten URL
  
}

else

{

  implement a shorten URL by algorithms
  
  store the relation of shorten URL and origin URL in database
  
}

# Click shorten URL
if(shorten URl in database)

{

  find the origin URL and go to the website
  
}

else

{

  output the 404 status
  
}
