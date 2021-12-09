var a = {};

function addnewarticle()

{
    var x=document.getElementById("myuser").value;

    var y =document.getElementById("myarticle").value;

    a[x]=y;

    localStorage.setItem('user', JSON.stringify(a));

    console.log('test')

}