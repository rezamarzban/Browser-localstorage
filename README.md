# Browser-localstorage
JavaScript to listing stored browser localstorage keys and datas

Note: JavaScript localstorage handler can not access cross domain localstorage. To accessing browser localstorage in each domain you should upload and run this script from itself domain, 
Or write below script in the browser address bar when you see a website domain:


JavaScript: document.write(fetch("https://raw.githubusercontent.com/marzban2030/Browser-localstorage/main/index.html").then(response => { return response; }););

List of compatible browsers from https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage that support localStorage:
![image](https://github.com/marzban2030/Browser-localstorage/raw/main/localStorageBrowsers.jpg)

