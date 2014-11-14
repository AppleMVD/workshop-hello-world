workshop-hello-world
====================

iOS app - Hello World (Workshop 2014, November, 14) - TechMeetupUY

1- Crear una pantalla con un <code>UITextField</code> (nombre) y un <code>UIButton</code> (Say hi!).
Al presionar el botón, mostrar una alerta saludando al usuario y usar el nombre ingresado en el UITextfield.

<img src="http://mitosystech.com/applemvd-resources/images/1.png" style="width: 50%;"/>
<img src="http://mitosystech.com/applemvd-resources/images/2.png" style="width: 200px;"/>

2- Embeber nuestro <code>UIViewController</code> en un Navigation Controller.

3- Arrastrar un <code>UITableViewController</code>.

4- Crear una clase que herede de <code>UITableViewController</code> y asignarla a nuestro controlador desde el Storyboard.

5- Trabajar en los siguientes métodos para mostrar los tipos de saludo:
```objective-c
- (NSInteger)numberOfSectionsInTableView:(UITableView *)tableView;
- (NSInteger)tableView:(UITableView *)tableView numberOfRowsInSection:(NSInteger)section;
- (UITableViewCell *)tableView:(UITableView *)tableView cellForRowAtIndexPath:(NSIndexPath *)indexPath;
```

6- Generar un "segue" desde nuestro botón "Say hi!" a nuestra tabla y pasarle el nombre.
Trabajar en:
```objective-c
- (void)prepareForSegue:(UIStoryboardSegue *)segue sender:(id)sender;
```

![alt tag](http://mitosystech.com/applemvd-resources/images/3.png)

7- Mostrar el saludo completo en un nuevo <code>UIViewcontroller</code>

![alt tag](http://mitosystech.com/applemvd-resources/images/4.png)
