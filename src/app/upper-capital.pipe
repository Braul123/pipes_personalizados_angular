import { Pipe, PipeTransform } from '@angular/core';

// Se define el decorador pipe con el nombre de la clase
@Pipe({
    name: 'upperCapital' // Este nombre es el que se utiliza para declarar la pipe en la interpolacion {{ data | upperCapital}}
})

// Se define la clase que hará todo el trabajo
export class UpperCapitalPipe implements PipeTransform {
   transform (value: string) {
       return value[0].toUpperCase() + value.substring(1).toLowerCase()
   } 
}