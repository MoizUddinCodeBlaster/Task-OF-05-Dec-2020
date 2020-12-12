class blockchain{

    constructor(cv,fullName,fatherName,address,email,cell,objective,objective1,persnolInformation,DateOfBirth,nicNo,martialStatus,religion,domiciel,language,acadmicEducationalBackground,intermediate,diploma,matriculation,experience,reference){
        this._cv=cv;
        this._fullName=fullName;
        this._fatherName=fatherName;
        this._address=address;
        this._email=email;
        this._cell=cell;
        this._objective=objective;
        this._objective1=objective1;
        this._persnolInformation=persnolInformation;
        this._DateOfBirth=DateOfBirth;
        this._nicNo=nicNo;
        this._martialStatus=martialStatus;
        this._religion=religion;
        this._domiciel=domiciel;
        this._language=language;
        this._acadmicEducationalBackground=acadmicEducationalBackground;
        this._intermediate=intermediate;
        this._matriculation=matriculation;
        this._diploma=diploma;
        this._experience=experience;
        this._reference=reference;

    }

      test(){
    console.log("my cv ="+this._cv);
    console.log("my fullName ="+this._fullName);
    console.log("my fathername = "+this._fatherName);
    console.log("my address ="+this._address);
    console.log("my email = "+this._email);
    console.log("my cell = "+this._cell);
    console.log("my objective ="+this._objective);
    console.log("my objective1 = "+this._objective1);
    console.log("my persnolInformation = "+this._persnolInformation);
    console.log("my date of birth = "+this._DateOfBirth);
    console.log("my nic no = "+this._nicNo);
    console.log("my martial status = "+this._martialStatus);
    console.log("my religion = "+this._religion);
    console.log("my domiciel ="+this._domiciel);
    console.log("my language = "+this._language);
    console.log("my acadmiceducationalbackground = "+this._acadmicEducationalBackground);
    console.log("my intermediate ="+this._intermediate);
    console.log("my matriculation = "+this._matirculation);
    console.log("my diploma ="+this._diploma);
    console.log("my experience = "+this._experience);
    console.log("my reference ="+this._reference);

}
}
var obj = new blockchain("CV","MoiZ uddin","xyz","a-8754874 north karachi","moiz.uddin1818@gnail.com","0303030303","objective","to seek achallinging posiyion in dynamc potential working enviroment.....................................................................! ","personal Information","27/03/199999","421014785854","singel","islam","karachi","urdu,english","acadmic educational background","intermediate(pre-enginerring)","matriculation","diploma","fresh","reference will be furninshed upon your request");
obj.test()
