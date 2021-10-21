import 'packagefluttermaterial.dart';
import 'packageflutterrendering.dart';

void main() = runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner false,
      theme ThemeData(backgroundColor Colors.white ),
      home Scaffold(
        appBar AppBar(
              leading Icon(Icons.arrow_back_rounded),
          title Text('Услуги',
            style TextStyle(
            fontSize 20,

          ),)

        ),
        body Center(
           child Text('Заданий отсуствуют',
               style TextStyle(fontSize 20)),

        ),


    ),
    );



  }
}
