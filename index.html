
 $('#save').on('click', function(){

    $('input[type="text"]').each(function(){    
        var id = $(this).attr('cooke');
        var value = $(this).val();
       localStorage.setItem(id, value);

    });   
});

$('#load').on('click', function(){
    $('input[type="text"]').each(function(){    
        var id = $(this).attr('id');
        var value = localStorage.getItem(id);

        $(this).val(value);

    }); 
});
           
var app = {
  cookiesPerClick: 1,
  
  cursors: [
    {},
    {
      cookiesPerSecond: 1,
      
    },
    {
      cookiesPerSecond: 2,
     
    },
    {
   
      cookiesPerSecond: 75,
      
    }
  ],
 
  cookies: function(value)
  {
    var cookie = document.getElementById('cookie');
    
    if(typeof value === 'undefined')
      return parseInt(cookie.textContent);
    
    var newValue = app.cookies() + value;
    
    if(newValue < 0)
      throw new Error('Pas assez de stock pour enlever ' + Math.abs(value) + ' cookies !');
    
    cookie.textContent = newValue;
  },
  
  /**
   * lance le jeu
   */
  run: function()
  {
    // le cookie !
    document.getElementById('cookie').addEventListener('click', function(){
      app.cookies(app.cookiesPerClick);
    }, false);
    
   
    document.getElementById('click').addEventListener('click', function(){
      try
      {
        app.cookies(-100);
        app.cookiesPerClick += 1;
      
      }
      
      
      
      catch(e)
      {}
    }, false),
      document.getElementById('click2').addEventListener('click', function(){
      try
      {
        app.cookies(-500);
        app.cookiesPerClick += 15;
      }
      catch(e)
      {}
    }, false)
    document.getElementById('click3').addEventListener('click', function(){
      try
      {
        app.cookies(-1000);
        app.cookiesPerClick += 175;
      }
      catch(e)
      {}
    }, false);
   
  document.getElementById('click4').addEventListener('click', function(){
      try
      {
        app.cookies(-100000);
        app.cookiesPerClick += 350;
      }
      catch(e)
      {}
    }, false);
    document.getElementById('click5').addEventListener('click', function(){
      try
      {
        app.cookies(-100000);
        app.cookiesPerClick += 800;
      }
      catch(e)
      {}
    }, false);
      for(var i = 1, c = app.cursors.length; i < c; ++i)
    {
      document.getElementById('cursor' + i).addEventListener('click', function(){
        try
        {
          app.cookies(-1 * app.cursors[i].cost);
          app.cursors[i].nbCursors++;
        }
        catch(e)
        {}
      }, false);
    }
   setInterval(function(){      for(var i = 1, c = app.cursors.length; i < c; ++i)        app.cookies(app.cursors[i].cookiesPerSecond * app.cursors[i].nbCursors);    }, 1000000);  }};
app.run();

