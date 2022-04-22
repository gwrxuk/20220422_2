import {fetch} from 'wix-fetch';

$w.onReady(function () {
	$w("#button1").onClick(function(event){
		let title = $w('#title').value;
		console.log(title);
		let content = $w('#content').value;
		console.log(content);
		
		let image = $w('#image').value;
		console.log(title);
		let total = $w('#total').value;
		console.log(content);


		let latitude = $w('#latitude').value;
		console.log(title);
		let longtidue = $w('#longitude').value;
		console.log(content);
  
        let url = "https://github.com/gwrxuk/20220422_2/?";
		$w("#html1").src = "";
	});

});

