
### js render  html 
```
<%= variablename %>
```

### ajax method
```
methods: {
					getsymptom() {
						var _self = this;
						//deme url http://127.0.0.1:8080/showonesymptoms?id=1241
						$.ajax({
							url: '/showonesymptoms?id=' + <%= sympid %>,
							// url:'/showonesymptoms?id=1241',
							//data:{res},
							type: 'get',
							success: (data) => {
								console.log(data)
								_self.sympitem = data[0],
									_self.sympname = data[0]["name"],
									_self.sympdesc = data[0]["desc"],
									_self.summary = data[0]["tickets"]

							}
						})
					},
          ```
       
### attribute bind
```
<div id="msgFrame" class="msgFrameDiv" v-on:click="closeMsgFrame()" v-if="seen">
```
        
### text bind
```
        {{name}}
```
