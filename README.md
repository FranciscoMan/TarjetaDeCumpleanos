# TarjetaDeCumpleaños
La siguiente aplicacion tiene como proposito mostrar un diseño simple para una tarjeta de felicitacion de cumpleaños
***
# Codigo XML
~~~
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    //Para ordenar los objetos utilizamos un relativeLayout
    <RelativeLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">
      //Declaracion de la vista de imagen que hace referencia a la imagen como si fuera un recurso en la carpeta drawable
        <ImageView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:src="@drawable/hb2" />
        //declaracion de la vista de texto de la felicitacion
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            //en esta declaracion siguiente puede modificar el mensaje
            android:text="Feliz cumpleaños, amigo!"
            //las siguientes declaraciones son para ajustar el mensaje a la parte superior de la imagen, darle color, tamaño y estilo
            android:layout_alignParentTop="true"
            android:textColor="#000000"
            android:textSize="25dp"
            android:textStyle="bold"
            tools:fontFamily="serif-monospace" />
      //declaracion de la vista de texto del mensaje de fondo con el destinatario
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            //aqui puedes modificar el texto del mensaje
            android:text="De: Carmelo"
            //las siguientes declaraciones son para ajustar el mensaje a la parte inferior derecha de la imagen y darle tamaño al texto
            android:layout_alignParentBottom="true"
            android:layout_alignParentEnd="true"
            android:layout_marginBottom="17dp"
            android:layout_marginEnd="13dp"
            android:layout_marginRight="13dp"
            android:layout_alignParentRight="true"
            android:textSize="25dp"/>



    </RelativeLayout>


</android.support.constraint.ConstraintLayout>
~~~
# Imagen de fondo
![Una imagen cualquiera](hb2.png "Imagen")
