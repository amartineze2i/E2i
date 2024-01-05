# E2i

## Organización del Código
Una convención común es organizar los elementos de la clase en el siguiente orden: `public`, metodo: `public slots`, `private`, `signals`, variable: `public`, y `private`. Esto ayuda a mantener una estructura clara y legible.

En los metodos ordenar por:
  void, bool, int, QString QVariant and others.

Las variables ordenar por:
  bool, int, QString QVariant and others.

Inicializar todas la variables por ejemplo
Qstring a = "";

## Nombres de Variables Miembro
Para las variables miembro, es una buena práctica usar un prefijo (como `m_`) para distinguirlas de las variables locales y los parámetros de las funciones. Esto mejora la legibilidad y evita confusiones.
