
var Cam01:GameObject;
var Cam02:GameObject;

function Start(){
	Cam01.active = true;
	Cam02.active = false;
}

function Update(){

	if(Input.GetKey(KeyCode.Q)){

		if(Cam01.active == true){
		
		Cam01.active = false;
		Cam02.active = true;

		}
		
		else{

			if(Cam01.active == false){
		
			Cam01.active = true;
			Cam02.active = false;

			}
		}
	}
}
