<center>

![](assets\univalle-rojopuro-159x226.jpg)

## APLICACIÓN WEB PARA LA GESTIÓN DE VACACIONES DE FUNCIONARIOS DE LA UNIVERSIDAD DEL VALLE

### BRYAN STEVEN BIOJÓ ROMERO

### 201629366

#### bryan.biojo@correounivalle.edu.co

## Director:

### OSCAR FERNANDO BEDOYA LEYVA, Ph.D.

#### oscar.bedoya@correounivalle.edu.co

#### Facultad de Ingeniería

#### Escuela de Ingeniería de Sistemas y Computación

#### Programa Académico de Ingeniería de Sistemas

#### Cali, Noviembre 21 de 2023

</center><br>

<center>

## Tabla de contenido

</center>

- Listado de Tablas

- Listado de Figuras

- Resumen

1. Planteamiento y Formulación del Problema

2. Justificación del Problema

   - 2.1. Justificación Académica.
   - 2.2. Justificación Económica.
   - 2.3. Justificación Social.

3. Objetivos

   - 3.1. Objetivo General.
   - 3.2. Objetivos Específicos.
   - 3.3. Resultados Esperados.

4. Alcances de la Propuesta

5. Marco Referencial

   - 5.1. Glosario.

   - 5.2. Estado del Arte.

   - 5.3. Marco Teórico.

6. Metodología

7. Presupuesto

8. Bibliografía

<center><br>

## Listado de tablas

</center>

- Tabla 1. Resultados esperados por objetivos específicos.

<center>

## Listado de figuras

</center>

- Figura 1.

<center>

## Resumen

</center>

<p style="text-align: justify;">
La tecnología ha sido un pilar fundamental en la evolución, permitiendo una mayor eficiencia, calidad y mejora constante de los procesos en diversas áreas, lo que a su vez ha impactado en nuestra calidad de vida. Tareas que eran repetitivas, lentas o complejas se han reducido o automatizado, lo que nos ha permitido enfocarnos en aspectos más relevantes.
</p>

<p style="text-align: justify;">
Sin embargo, muchas compañías e instituciones todavía realizan numerosas tareas manuales, las cuales consumen tiempo y son propensas a errores. En el caso de las universidades públicas y en particular en la Universidad del Valle (Colombia) esto se puede observar en diversos procesos como, por ejemplo, el cálculo de los periodos de vacaciones de los funcionarios. Este proceso es de vital importancia y requiere atención ya que deben tenerse en cuenta aspectos como: cuándo se pueden solicitar las vacaciones, cuántos días pueden tomar los funcionarios de acuerdo a su régimen, verificar el correcto diligenciamiento de los formatos de solicitud y reintegro, entre otras etapas.
</p>

<p style="text-align: justify;">
Este trabajo de grado se centra en el desarrollo de una aplicación web que apoye a los funcionarios de la Universidad del Valle en el proceso de gestión de vacaciones (solicitudes y reintegros) con el fin de que sea más rápido y se minimicen posibles errores debido a la intervención humana. Para lograr esto, es necesario identificar cada una de las etapas que se llevan a cabo para tramitar estas solicitudes, así como sus respectivas condiciones y/o restricciones.
</p><br>

## 1. Planteamiento y Formulación del Problema

<p style="text-align: justify;">
Actualmente una parte crucial del proceso de gestión de vacaciones de los funcionarios de la Universidad del Valle es el cálculo manual de las fechas de salida y reintegro. Este proceso es llevado a cabo individualmente por parte de los propios funcionarios.
</p>

<p style="text-align: justify;">
En general, el proceso de solicitud de vacaciones es el siguiente:
</p>

- El funcionario debe calcular manualmente el periodo de vacaciones seleccionado teniendo en cuenta su régimen, el cual determina el número de días a los que tiene derecho según la ley que rige a las universidades públicas colombianas.
- Una vez realizado el cálculo, el funcionario debe diligenciar y firmar una solicitud indicando la fecha de inicio de las vacaciones, el periodo al que corresponden y si se tomarán durante el periodo individual o colectivo. Si las vacaciones se quieren tomar de forma colectiva y el funcionario no ha cumplido con los plazos establecidos para solicitarlas, debe diligenciar un formato adicional.
- A continuación, el funcionario envía la solicitud al director(a) de la unidad académica o administrativa o a su jefe inmediato para su validación y revisión.
- El director(a) o jefe inmediato remite la información a la facultad, instituto o dependencia para su revisión y posterior envío al área de RRHH (Recursos Humanos).
- RRHH verifica nuevamente la solicitud y determina si el funcionario cumple con los requisitos. Si cumple, se inicia el trámite administrativo para el pago de las vacaciones y se notifica al funcionario la aprobación de su solicitud. En caso contrario, se notifica al director(a) de la unidad académica o administrativa o al jefe inmediato la razón por la cual no se aprueba la solicitud y después este(a) se lo comunica al funcionario.

<p style="text-align: justify;">
En cuanto al reintegro a las labores, el proceso es el siguiente:
</p>

- El funcionario debe completar y firmar un formato denominado P4, indicando si el motivo del reintegro es por finalización del periodo de vacaciones o anticipado debido a necesidad del servicio. En caso de un reintegro anticipado, debe registrar los días pendientes para que se puedan conceder posteriormente.
- A continuación, la solicitud pasa por el mismo trámite descrito en la solicitud de vacaciones a partir del tercer punto.

<p style="text-align: justify;">
Como se puede observar, el problema radica en que si el funcionario no realiza correctamente el cálculo del período de vacaciones, la solicitud será rechazada. Además, resulta laborioso conocer los días pendientes de vacaciones de un funcionario y el estado de las solicitudes de vacaciones o reintegros, ya que todo el proceso se realiza de forma manual.
</p>

<p style="text-align: justify;">
Por lo tanto, la pregunta de investigación que orienta este trabajo de grado es: ¿Es posible desarrollar una aplicación web que permita determinar el estado actual de las vacaciones de cada funcionario, controlar fechas calendario, automatizar el cálculo de estas fechas teniendo en cuenta todas las restricciones y registrar la aceptación o rechazo de las solicitudes.
</p><br>

## 2. Justificación del Problema

### 2.1. Justificación Académica

<p style="text-align: justify;">
Este trabajo de grado busca ampliar los conocimientos adquiridos en asignaturas como: Desarrollo de Software, Bases de Datos y Aplicaciones en la WEB y Redes Inalámbricas para desarrollar una aplicación web que agilice el proceso de gestión de vacaciones de los funcionarios de la Universidad del Valle. Además, este trabajo proporcionará una experiencia de aprendizaje en desarrollo web, abarcando aspectos de usabilidad, seguridad, calidad, entre otros.
</p>

### 2.2. Justificación Económica

<p style="text-align: justify;">
El proceso actual de gestión de vacaciones conlleva costos significativos y un gasto considerable en papelería. Además, se enfrenta al problema de solicitudes rechazadas, lo que implica la devolución de documentos y la repetición del proceso. Los errores en el cálculo de vacaciones pueden tener un impacto económico directo en los salarios de los funcionarios, resultando en pagos incorrectos. La implementación de una aplicación web para agilizar y automatizar este proceso permitiría un registro, control y seguimiento más eficientes, reduciendo los costos asociados a este proceso.
</p>

### 2.3. Justificación Social

<p style="text-align: justify;">
Este trabajo de grado impacta positivamente a la Universidad del Valle y puede servir como referencia para optimizar procesos similares dentro de esta o en otras instituciones. La automatización agiliza el acceso a información, fomentando la transparencia y equidad en la gestión. Además, mejora la eficiencia y efectividad en la toma de decisiones.
</p><br>

## 3. Objetivos

### 3.1. Objetivo General

<p style="text-align: justify;">
Desarrollar una aplicación web que permita la gestión de vacaciones de los funcionarios de la Universidad del Valle.
</p>

### 3.2. Objetivo Específicos

<ul style="text-align: justify;">
<li>Realizar la especificación del proceso de gestión de vacaciones mediante diagramas de modelado de procesos de negocio (BPM).</li>
<li>Diseñar e implementar un módulo para el control de fechas calendario de los periodos de vacaciones.</li>
<li>Diseñar e implementar un módulo para determinar el estado de vacaciones de los funcionarios.</li>
<li>Diseñar e implementar un módulo para la solicitud de vacaciones.</li>
<li>Diseñar e implementar un módulo de reintegro de vacaciones.</li>
<li>Evaluar la efectividad de los módulos desarrollados contra las diferentes etapas del proceso de forma manual.</li>

### 3.3. Resultados Esperados

| Objetivos Específicos | Producto(s) Esperados                                                                                                                        |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo 1            | Diagramas de BPM que muestren de forma clara y visual el proceso de gestión de vacaciones.                                                   |
| Objetivo 2            | Código fuente del módulo de control de las fechas calendario de los periodos de vacaciones.                                                  |
| Objetivo 3            | Código fuente del módulo para la determinación del estado de vacaciones de los funcionarios.                                                 |
| Objetivo 4            | Código fuente del módulo para la solicitud de vacaciones de los funcionarios.                                                                |
| Objetivo 5            | Código fuente del módulo de reintegro de vacaciones de los funcionarios.                                                                     |
| Objetivo 6            | Comparación de los tiempos empleados por los funcionarios al realizar la solicitud tanto de forma manual como a través de la aplicación web. |

<center>

**Tabla 1.** Resultados esperados por objetivos específicos.

</center><br>

## 4. Alcances de la Propuesta

<p style="text-align: justify;">
Este proyecto de grado se limitará al desarrollo de la aplicación web que permita la gestión del proceso de vacaciones de los funcionarios de la Universidad del Valle. El prototipo se realizará utilizando datos sintéticos.
</p><br>

## 5. Marco Referencial

<p style="text-align: justify;">
Este proyecto de grado se limitará al desarrollo de la aplicación web que permita la gestión del proceso de vacaciones de los funcionarios de la Universidad del Valle. El prototipo se realizará utilizando datos sintéticos.
</p><br>

### 5.1. Glosario

<ul style="text-align: justify;">
<li> <strong>Aplicación web:</strong> Aplicación informática que se accede a través de un navegador web y que funciona en internet.
<li><strong>Automatización de procesos:</strong> Uso de tecnología para realizar tareas y actividades de forma automática sin intervención humana con el objetivo de aumentar la eficiencia y reducir errores en los procesos de una organización.
<li><strong>Director:</strong> Persona que ocupa una posición de liderazgo en una organización, empresa, institución o grupo. Su rol implica la toma de decisiones importantes, la supervisión de actividades y la dirección de equipos o departamentos.</li>
<li><strong>Facultad:</strong> En el contexto académico, división o departamento dentro de una universidad que se especializa en un campo específico de estudio.</li>
<li><strong>Formato P4:</strong> Formato utilizado para la solicitud y registro de vacaciones en algunas organizaciones.</li>
<li><strong>Funcionario:</strong> Persona que ocupa un cargo o posición en una organización, institución gubernamental o empresa y desempeña funciones y responsabilidades específicas en el cumplimiento de sus deberes. En el contexto universitario, los funcionarios pueden incluir tanto al personal académico (profesores, investigadores) como al personal administrativo (personal de apoyo, directivos, personal de recursos humanos, etc.).</li>
<li><strong>Módulo:</strong> Parte o componente de un sistema más grande o de un programa informático que cumple una función específica y generalmente se puede usar de manera independiente o en conjunto con otros módulos.</li>
<li><strong>Período de vacaciones:</strong> Tiempo en el cual un empleado tiene derecho a tomar un descanso remunerado del trabajo.</li>
<li><strong>Recursos humanos (RRHH):</strong> Departamento encargado de atraer, retener y desarrollar talento humano, así como garantizar que los empleados tengan un ambiente laboral adecuado y se cumplan las leyes laborales y regulaciones.</li>
<li><strong>Régimen:</strong> Conjunto de normas, reglas y políticas que regulan las condiciones laborales, derechos, deberes y beneficios de los empleados de una organización.</li>
<li><strong>Reintegro de vacaciones:</strong> Proceso en el cual un empleado retorna a sus actividades laborales después de haber disfrutado de un período de vacaciones.</li>
<li><strong>Solicitud de vacaciones:</strong> Petición formal de un empleado para obtener permiso o autorización para tomar vacaciones.</li>
<li><strong>Unidad académica:</strong> Entidad dentro de una institución educativa que agrupa y organiza programas académicos relacionados con un campo particular de estudio o disciplina.</li>
<li><strong>Unidad administrativa:</strong> Entidad dentro de una organización, institución o empresa que se encarga de llevar a cabo tareas y responsabilidades relacionadas con la gestión y administración de los recursos, procesos y funciones de la entidad en cuestión.</li>
<li><strong>Universidad:</strong> Institución de educación superior que ofrece programas de enseñanza, investigación y extensión académica.</li>
<li><strong>Vacaciones colectivas:</strong> Período de descanso otorgado a todos los empleados de una organización al mismo tiempo.</li>
<li><strong>Vacaciones individuales:</strong> Período de descanso otorgado a un empleado de manera individual, según su derecho y acuerdo laboral.</li>
</ul><br>

### 5.2. Estado del Arte

#### 5.2.1 Implementación de un sistema Web para Talento Humano en la Universidad Central de Ecuador

<p style="text-align: justify;">
La Dirección de Talento Humano de la Universidad Central del Ecuador (UCE) enfrentaba diversos desafíos en la gestión de solicitudes relacionadas con el personal administrativo, incluyendo vacaciones, licencias, permisos, y el registro de sanciones. Su sistema de gestión, desarrollado en la herramienta empresarial PowerBuilder, era obsoleto, ineficiente, y no se adecuaba a las necesidades actuales. Además, procesos como la autorización y seguimiento de solicitudes de vacaciones se llevaban a cabo manualmente, lo que requería una cantidad significativa de tiempo y esfuerzo, causaba demoras en el procesamiento de solicitudes, propiciaba errores en los cálculos de días, resultaba en la pérdida de información crucial y no permitía la visibilidad del estado de estas solicitudes.
</p>

<p style="text-align: justify;">
En el caso de las solicitudes de vacaciones, el empleado debía presentar un oficio a su supervisor, quien decidía si aprobar o no la solicitud. En caso de aprobación, esta se enviaba a la Dirección de Talento Humano y era registrada por el Analista encargado del proceso. Todos los registros se consolidaban en una hoja de Excel con aproximadamente 1000 registros, cada una con atributos como nombre, departamento, régimen, fecha de ingreso, número de permisos en días y horas, saldos de vacaciones pendientes, entre otros.
</p>

<center>

![](assets\figs\fig1_archivo-vacaciones.png)

**Figura 1.** Archivo de vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
Después de registrar la información en la hoja de Excel, se generaba un documento en Word que requería ser personalizado con los datos del empleado antes de imprimirlo y enviarlo al director(a) de la Dirección de Talento Humano para su firma. Posteriormente, el documento firmado se entregaba al interesado.
</p>

<center>

![](assets\figs\fig2_autorizacion-vacaciones-anuales.png)

**Figura 2.** Autorización de vacaciones anuales. Tomado de [].

</center>

<p style="text-align: justify;">
Para afrontar estos desafíos, se diseñó y puso en marcha un sistema web utilizando Java como lenguaje de programación, JavaServer Faces (JSF) e Hibernate como frameworks, Wildfly como servidor de aplicaciones y Oracle Express 11g como motor de bases de datos para asegurar que esta fuese robusta y escalable. En el proceso de desarrollo se aplicó la metodología eXtreme Programming (XP) con el objetivo de garantizar que el sistema se creara de acuerdo con las necesidades reales de la Dirección de Talento Humano.
</p>

<p style="text-align: justify;">
El desarrollo del sistema web se enfocó en validar los siguientes objetivos:
</p>

- Identificar las necesidades y requerimientos funcionales del sistema.
- Gestionar la concesión de vacaciones de forma automática.
- Gestionar el registro de permisos personales.
- Gestionar la emisión de licencias de forma automática.
- Gestionar el registro de sanciones.
- Generar informes y reportes.

<br><p style="text-align: justify;">
Con la implementación del módulo, se logró optimizar el tiempo en los diferentes procesos mencionados, permitiendo que las solicitudes de los funcionarios fuesen atendidas de forma rápida y eficiente.

</p>

<center>

![](assets\figs\fig3_prototipo-menu-principal.png)

**Figura 3.** Prototipo del menú principal. Tomado de [].

</center>

<center>

![](assets\figs\fig4_formulario_registro_vacaciones.png)

**Figura 4.** Formulario de registro de vacaciones. Tomado de [].

</center>

<center>

![](assets\figs\fig5_formato-autorizacion-vacaciones.png)

**Figura 5.** Formato de autorización de vacaciones autogenerado. Tomado de [].

</center>

<p style="text-align: justify;">
El proceso de solicitud de vacaciones se consolidó de la siguiente forma:
</p>

<center>

![](assets\figs\fig6_nuevo-registro-vacaciones.png)

**Figura 6.** Nuevo Registro de Vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
De todo el proceso de desarrollo del sistema web se obtuvieron las siguientes conclusiones:
</p><br>

- La aplicación web contribuyó en gran medida a establecer procesos específicos para la concesión de vacaciones y permisos que antes no estaban claramente definidos.
- La gestión automatizada de la concesión de vacaciones permitió mantener registros actualizados de los saldos de vacaciones, lo que agilizó la emisión de autorizaciones y garantizó respuestas rápidas a las solicitudes.
- La información administrativa relacionada con los empleados de la UCE pudo centralizarse en los servidores de la Dirección de Tecnología.
- Se logró segmentar la información de los empleados, evitando la carga masiva de datos, como ocurría en el sistema anterior de Talento Humano.

#### 5.2.2 Módulo de Gestión del Personal para el Área de Recursos Humanos para el Hospital San Vicente de Paúl

<p style="text-align: justify;">
El departamento de Recursos Humanos del Hospital San Vicente de Paúl en Ibarra, Ecuador, enfrentaba la necesidad de implementar un módulo de gestión de personal para manejar eficazmente aspectos como sanciones, estadísticas, días festivos, vacaciones, contratos, reportes, licencias médicas, selección de candidatos y nómina de los empleados. Estos procesos anteriormente se gestionaban de forma manual.
</p>

<center>

![](assets\figs\fig7_esquema-general-proyecto-hsvdp.png)

**Figura 7.** Esquema general del proyecto Hospital San Vicente de Paúl. Tomado de [].

</center>

<p style="text-align: justify;">
Para afrontar esta problemática, se desarrolló e implementó un módulo web utilizando PHP con el framework Symfony, siguiendo el enfoque del patrón MVC (Modelo-Vista-Controlador). La base de datos se gestionó mediante MySQL. En cuanto a la metodología de trabajo, se empleó el Proceso Unificado de Rational (RUP).
</p>

<p style="text-align: justify;">
El proceso de solicitud y aprobación de vacaciones se consolidó de la siguiente manera:
</p>

- El usuario especifica la acción a ejecutar, en este caso: Registros de Vacaciones.
- El sistema solicita el ingreso del nombre del empleado.
- El sistema verifica que el registro exista.
- El usuario ingresa en el sistema la información de las vacaciones.
- El usuario debe verificar y registrar la fecha de inicio y fin de la solicitud de vacaciones.
- El usuario asigna vacaciones al empleado.
- El sistema actualiza los reportes.

<br><center>

![](assets\figs\fig8_diagrama-secuencia-controlar-vacaciones.png)

**Figura 8.** Diagrama de secuencia: Controlar vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
El panel de vacaciones resultante incluía todas las operaciones relacionadas con la gestión de la información de las vacaciones de los empleados, como: crear nueva vacación, eliminar vacación, generar informe de vacaciones, editar vacación, imprimir vacación.
</p>

<center>

![](assets\figs\fig9_panel-vacaciones.png)

**Figura 9.** Panel de vacaciones. Tomado de [].

</center>

<center>

![](assets\figs\fig10_formulario-registro-nueva-vacacion.png)

**Figura 10.** Formulario de registro de nueva vacación. Tomado de [].

</center>

<center>

![](assets\figs\fig11_formato-solicitud-vacacion.png)

**Figura 11.** Formato de solicitud de vacación. Tomado de [].

</center>

<p style="text-align: justify;">
También se podían generar reportes del estado de vacaciones de los empleados:
</p>

<center>

![](assets\figs\fig12_reportes-registros-vacaciones-empleados.png)

**Figura 12.** Reporte de los registros de vacaciones de los empleados. Tomado de [].

</center>

<p style="text-align: justify;">
De todo el proceso de desarrollo se obtuvieron las siguientes conclusiones:
</p>

- Se optimizó de manera eficiente la gestión de los registros de los empleados.
- Se logró una integración ordenada de los procesos en el departamento de Recursos Humanos, lo que resultó en una mayor eficiencia en la ejecución de cada actividad.
- La centralización de la información posibilitó la generación de informes y estadísticas para su análisis correspondiente.

#### 5.2.3 Sistema Web para la Gestión del Recurso Humano de la Dirección Provincial de Educación de Imbabura SIG-RRHH mediante la utilización del framework Symfony

<p style="text-align: justify;">
La Dirección Provincial de Educación de Imbabura, Ecuador presentaba problemas para gestionar la información de su unidad de Recursos Humanos, ya que esta era almacenada en papel y en procesadores de texto, dificultando los trámites administrativos y con el riesgo latente de pérdida de información. 
</p>

<p style="text-align: justify;">
Para abordar este desafío, se procedió a desarrollar e implementar un módulo web en PHP, aprovechando Symfony como framework junto al patrón MVC (Modelo-Vista-Controlador). Para la gestión de la base de datos, se eligió MySQL como motor. En lo que respecta a la metodología de trabajo, se optó por la aplicación de RUP (Proceso Unificado de Rational).
</p>

<p style="text-align: justify;">
Para el apartado de vacaciones se consolidó el siguiente proceso:
</p>

- El usuario define la acción deseada, en este caso, la solicitud de Registro de Vacaciones.
- El sistema presenta el filtro de búsqueda, donde el usuario debe introducir la cédula del empleado al que se le asignarán las vacaciones.
- El sistema comprueba la existencia del parámetro de búsqueda, es decir, el número de cédula. Si se encuentra, muestra el filtro de búsqueda correspondiente.
- Si el sistema detecta el parámetro de búsqueda, procede a realizar la consulta basada en dicho parámetro.
- En caso de no proporcionar el parámetro de búsqueda, el sistema muestra automáticamente el filtro de consulta.
- Una vez que se muestra la consulta, el usuario accede a la acción de vacaciones.
- Se procede a ingresar los datos requeridos en el formulario.
- Se efectúa una validación de fechas al ingresar cada una de ellas y se verifica la integridad de los datos del registro de vacaciones.
- El estado del sistema cambia a ‘Listo’ para ejecutar la acción correspondiente.
- Cuando el sistema detecta fechas inválidas, se muestra el mensaje de error "Fecha inválida".
- El usuario tiene la opción de volver a ingresar las fechas para una nueva verificación en caso de errores.
- Si el sistema confirma que las fechas ingresadas son correctas, procede al almacenamiento del registro correspondiente.
- El usuario visualiza la acción relacionada con las vacaciones, la cual puede imprimirse para su legalización correspondiente.

<br><center>

![](assets\figs\fig13_diagrama-actividades-proceso-vacaciones.png)

**Figura 13.** Diagrama de actividades - Proceso de vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
Las conclusiones obtenidas del desarrollo fueron las siguientes:
</p>

- El sistema desarrollado proporcionó una contribución significativa a la Unidad de Recursos Humanos de la Dirección Provincial de Educación de Imbabura, simplificando el registro y la gestión del personal, reduciendo la carga de tareas repetitivas y generando resultados más eficientes.
- El sistema optimiza una variedad de procesos relacionados con la gestión de personal, que incluyen nombramientos, cambios, traslados, renuncias, licencias médicas, jubilaciones, vacaciones, así como el registro de permisos ocasionales y nuevas contrataciones.
- La elección de software libre garantiza que el sistema pueda ser continuamente desarrollado, mejorado y adaptado. Esto asegura la longevidad y la flexibilidad del sistema, lo cual es fundamental en entornos en constante evolución.

#### 5.2.4 Diseño e Implementación de un Sistema para Automatizar la Gestión de Procesos de Contratación de Empleados, Solicitud de Vacaciones y Generación de Certificados Laborales

<p style="text-align: justify;">
La empresa Talentos y Tecnología S.A.S se enfrentaba a un desafío significativo en la gestión de sus contratos laborales. Estos contratos se realizaban en documentos de Word, sin ninguna medida de seguridad. Cada vez que surgía una nueva contratación o el reingreso de un empleado, el responsable debía buscar el contrato relevante, abrir el documento en Word y completar manualmente la información personal del empleado antes de imprimirlo. Además, no se llevaba un registro de las modificaciones realizadas en los contratos laborales, lo que podía derivar en riesgos legales.
</p>

<p style="text-align: justify;">
De igual manera, se enfrentaban a desafíos relacionados con las solicitudes de vacaciones por parte de los empleados. Los tiempos de respuesta eran tardíos, faltaba información sobre los derechos a vacaciones, así como del procedimiento para solicitarlas.
</p>

<p style="text-align: justify;">
Para el desarrollo de la solución, se utilizó el lenguaje de programación PHP. Como motor de bases de datos, se utilizó SQL Server, que era el motor de bases de datos empleado en la empresa. En lo que respecta al patrón de arquitectura, se optó por MVC (Modelo-Vista-Controlador).
</p>

<center>

![](assets\figs\fig14_diagrama-actividades-solicitud-vacaciones.png)

**Figura 14.** Diagrama de actividades - Solicitud de vacaciones. Tomado de [].

</center>

<p style="text-align: justify;">
Del proceso de desarrollo se obtuvieron las siguientes conclusiones:
</p>

- La implementación de la aplicación web tuvo un impacto positivo tanto en el personal de gestión de recursos humanos como en los empleados, al optimizar procesos como la generación de certificados laborales, las solicitudes de vacaciones y las contrataciones.
- La aplicación web facilitó el acceso de los empleados a sus solicitudes, ofreciendo un proceso sencillo y rápido, al tiempo que garantizaba la privacidad y confidencialidad de la información.
- Las aplicaciones de software, en particular las aplicaciones web, siguen siendo una solución efectiva para abordar diversas necesidades dentro de las organizaciones gracias a sus ventajas y beneficios.
- La accesibilidad de los empleados a través de un navegador web elimina la necesidad de instalar la aplicación en sus dispositivos, lo que simplifica el proceso y asegura que los cambios en la aplicación se reflejen de inmediato para todos los usuarios.
- La aplicación web ofrece flexibilidad y capacidad de respuesta, lo que resulta especialmente útil en situaciones que requieren modificaciones urgentes en la aplicación para mejorar la eficiencia y eficacia de los procesos.

### 5.3. Marco Teórico

- **Diagrama de actividades:** Representación gráfica que muestra el flujo de actividades o procesos en un sistema o proyecto.
- **eXtreme Programming (XP)**: Enfoque de desarrollo de software ágil que se centra en la comunicación y la flexibilidad, con énfasis en la entrega continua de software de alta calidad.
- **Excel:** Aplicación de hoja de cálculo ampliamente utilizada para realizar cálculos, crear gráficos y organizar datos.
- **Framework:** Conjunto de herramientas y reglas que facilita el desarrollo de software al proporcionar una estructura y funcionalidades comunes para los programadores. También es conocido como ‘Marco de trabajo’.
- **Hibernate:** Framework de mapeo objeto-relacional que facilita el almacenamiento y recuperación de objetos Java en una base de datos.
- **Java:** Lenguaje de programación de propósito general ampliamente utilizado en el desarrollo de aplicaciones y servicios en línea.
- **JavaServer Faces (JSF):** Framework de desarrollo de Java para crear interfaces de usuario web basadas en componentes.
- **Modelo-Vista-Controlador (MVC):** Patrón de diseño de software que separa la lógica de una aplicación en tres componentes: modelo (representación de la información), vista (información y lógica de negocio) y controlador (El que responde a eventos, usualmente acciones del usuario).
- **MySQL:** Sistema de gestión de bases de datos de código abierto que se utiliza comúnmente para almacenar y administrar datos.
- **Oracle Express:** Edición de la base de datos Oracle que ofrece funcionalidades de nivel empresarial en un formato ligero.
- **PHP:** Lenguaje de programación ampliamente utilizado en el desarrollo de aplicaciones y sitios web dinámicos.
- **PowerBuilder:** Herramienta de desarrollo de software utilizada para crear aplicaciones empresariales.
- **Prototipo:** Versión inicial o modelo de un producto o sistema, utilizada para probar conceptos y funcionalidades.
- **Registro:** Acto de almacenar información o datos en una base de datos para su posterior recuperación.
- **Reportes:** Documentos o informes que presentan datos, resultados o información detallada sobre un tema específico.
- **Proceso Unificado de Rational (RUP):** Metodología de desarrollo de software que se centra en la gestión de proyectos y la calidad del software.
- **Sistema:** Conjunto de componentes interconectados que trabajan juntos para lograr un propósito específico.
- **SQL Server:** Sistema de gestión de bases de datos desarrollado por Microsoft.
- **Symfony:** Framework de desarrollo de aplicaciones web en PHP que facilita la creación de aplicaciones web robustas.
- **Web:** World Wide Web, red de información global que se accede a través de Internet.
- **Word:** Procesador de texto ampliamente utilizado para crear y editar documentos de texto.

## 6. Metodología

### 6.1 Actividades a realizar

**Objetivo 1:** Realizar la especificación del proceso de gestión de vacaciones mediante diagramas de modelado de procesos de negocio (BPM).

- A1: Investigar y realizar un análisis sobre el procedimiento de solicitud y reintegro de vacaciones en la Universidad, incluyendo todas las consideraciones y reglamentación pertinentes.

- A2: Elaborar diagrama de BPM que detalle de manera específica los procesos de solicitud y reintegro de vacaciones.

**Objetivo 2:** Diseñar e implementar un módulo para el control de fechas calendario de los periodos de vacaciones.

- A3: Realizar un análisis detallado de los requisitos específicos del módulo de control de fechas calendario para los periodos de vacaciones, considerando las tecnologías adecuadas para el desarrollo.

- A4: Desarrollar y probar el módulo empleando las tecnologías seleccionadas para asegurar que pueda integrarse y cumpla con las funcionalidades requeridas, manteniendo buenas prácticas de programación y seguridad.

**Objetivo 3:** Diseñar e implementar un módulo para determinar el estado de vacaciones de los funcionarios.

- A5: Realizar un análisis detallado de los requisitos y necesidades del módulo de estado de vacaciones para determinar el estado de vacaciones de los funcionarios, considerando las tecnologías adecuadas para el desarrollo.

- A6: Desarrollar y probar el módulo, empleando las tecnologías seleccionadas para asegurar que pueda integrarse y cumpla con las funcionalidades requeridas, manteniendo buenas prácticas de programación y seguridad.

**Objetivo 4:** Diseñar e implementar un módulo para la solicitud de vacaciones

- A7: Realizar un análisis detallado de los requisitos y necesidades del módulo de solicitud de vacaciones, considerando las tecnologías adecuadas para el desarrollo.

- A8: Desarrollar y probar el módulo, empleando las tecnologías seleccionadas para asegurar que pueda integrarse y cumpla con las funcionalidades requeridas, manteniendo buenas prácticas de programación y seguridad.

**Objetivo 5:** Diseñar e implementar un módulo de reintegro de vacaciones.

- A9: Realizar un análisis detallado de los requisitos y necesidades del módulo de reintegro de vacaciones, considerando las tecnologías adecuadas para el desarrollo.

- A10: Desarrollar y probar el módulo, empleando las tecnologías seleccionadas para asegurar que pueda integrarse y cumpla con las funcionalidades requeridas, manteniendo buenas prácticas de programación y seguridad.

**Objetivo 6:** Evaluar la efectividad de los módulos desarrollados contra las diferentes etapas del proceso de forma manual.

- A11: Realizar comparación estadística sobre la efectividad del proceso de solicitud y reintegro de vacaciones con la aplicación web, versus el proceso manual.

<center>

[**Tabla 2.** Actividades a realizar.](documents\pdf\t2_actividades-a-realizar.pdf)

</center>

### 6.2 Cronograma de actividades

## 7.2 Presupuesto

### 7.1 Presupuesto total del proyecto

### 7.2 Presupuesto detallado del personal

### 7.3 Presupuesto detallado del hardware

## Bibliografía

-
