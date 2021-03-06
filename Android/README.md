# Engineer 1

- ViewGroups
	- RelativeLayout, LinearLayout, ScrollViews  
	- Propiedades básicas de cada uno
- Views
	- Tipos: ImageView, Button, TextView, EditText, TextInputEditText.  
	- Propiedades de cada uno
	- ClickListeners programáticos vs xml  
	- Estados: visibles, invisibles, etc.
- Activities
	- Definición
	- Ciclo de vida
	- Implementación
- Fragments
	- Definición  
	- Ciclo de vida  
	- Formas de implementación (xml <fragment> | programáticamente)  
	- FragmentManager
- Broadcast Receivers
	- Definición
	- Ciclo de vida  
	- Formas de implementación (xml <fragment> | programáticamente)  
- Services
	- Definición
	- Usos comunes
- Content providers
	- Definición
- Manifest
	- Tipos de tags. Componentes de Android (Activities, BReceivers, Services, CProviders)
	- Permisos (definición). Configuración de la aplicación (icons, name, theme, etc.)
- Gradle
	- Para que sirve?  
	- Build.gradle (proyecto y modulo app. Tasks de build y compilación)
- Manejo de IDE
	- Android Studio - InteliJ  
	- Lectura de logs  
	- AVD
- Adapters
	- BaseAdapter. Derivados (SimpleCursorAdapter, ArrayAdapter, etc.)
- Intent
	- Definicion. Adicionales: putExtra, etc.  
	- Intent implícitos vs explícitos
- Modal Views
	- Alerts  
	- Dialogs
	- Progressbar
- Manejo basico de recursos
	- Agregar y usar strings, dimens, colors, etc.

# Engineer 2

- ViewGroups
	- ConstraintLayout, CoordinatorLayout, SwipeRefreshLayout  
	- RelativeLayout vs ConstraintLayout  
	- Responsive UI
- CustomViews
	- Cómo definirlos.  
	- XML involucrados (attr.xml, styles.xml, colors.xml, etc)  
	- Shapes
- Activities
	- Ciclo de vida (callbacks y qué se ejecuta en cada uno)  
	- Estado de un activity (background, foreground, superpuesto por un dialogo modal, etc).
- Fragments
	- Ciclo de vida (callbacks y qué se ejecuta en cada uno)  
	- Relación con ciclo de vida de un activity  
	- Comunicación entre Fragment y Activity. (Callbacks)  
	- Comunicación entre Fragments (Callbacks)
- Broadcast Receivers
	- Implementación  
	- Definición por manifest vs prográmaticamente - Definir sus intent action.  
	- LocalBroadcastManager, por qué y cuándo usarlo (Mantener los eventos dentro del contexto de la app)
- Services
	- Tipos de services. (Services vs BoundServices)  
	- Implementación (Extendiendo clase Service - clase IntentService)  
	- Diferencias entre Service vs IntentService.  
	- Formas de arrancarlos y detenerlos
- Content providers
	- Tipos: Genericos vs Custom.  
	- Cómo usar los genéricos
- Manifest
	- Intent filters, Intent actions, Data types, etc.
- Permisos
	- Manifest permissions vs Runtime permissions.  
	- Implementación de runtime permissions.
- Material design
	- Conocimiento general de componentes de material design. 						Implementación.  
	- Librerías (legacy: support - androidx)
- Conectividad
	- Retrofit | Retrofit2 (Conocimientos basicos)  
	- Serialización y deserialización de manera nativa  
	- Librerías para serialización y deserialización (Gson, Jackson, etc.)
- Gradle
	- settings.gradle (dependencias de modulos en un mismo bundle)  
	- gradle.properties
- Manejo de IDE
	- Breakpoints y debugger  
	- Emuladores: propios de AS vs Genymotion  
	- SDK Manager  
	- Layout inspector
- Adapters
	- RecyclerView.Adapter con ViewHolder pattern
- Intent
	- Intent services, Intent filters  
	- PendingIntents
- Tests
	- Unit Test (Conocimientos básicos)  
	- Instrumented Test (Conocimientos básicos)
- Hilos
	- Conocimientos de hilos en Android  
	- Thread UI
- AsyncTask
	- Definición  
	- Implementación
- ViewPager
	- Que es? Implementación  
	- PagerAdapter
- Almacenamiento
	- Ubicación (estructura de almacenamiento)  
	- SharedPreferences (contexto global o activity)  
	- SQLite. Implementación  
	- Interno vs Externo (device memory vs SD external storage)
- Notificaciones
	- Definición. Implementación  
	- Notification builder  
	- Notification Manager
- App configuration
	- Rotación de pantalla  
	- Densidades  
	- Internacionalización
- Tags xml en layouts
	- Include  
	- Merge
	- Fragment
- Arquitectura android (ART)
	- Capas de arquitectura
- Widgets
	- Estáticos y dinámicos

# Engineer 3

- CustomViews
	- Manejo de gradientes y sombras, etc.
- ViewModel
	- ¿Qué es? ¿Para qué sirve?  
	- Casos de aplicación: Ej: comunicación entre dos fragments dentro de un activity
	- Implementación
	- Ciclo de vida del ViewModel
- Fragments
	- Comunicación entre Fragments por ViewModel
- Services
	- Implementación de BoundServices
- Content providers
	- Implementación custom  
	- Manejador de concurrencia (definir operaciones CRUD con syncronized)
- Permisos
	- Librerías para pedir permisos (Ej: Dexter)
- Material design
	- Animaciones, transiciones, transformaciones  
	- Material design guidelines - brandlines
- Gradle
	- BuildVariants: main, release, prod, debug, etc.  
	- Custom tasks, flavors, dimensiones
- Tests
	- Unit Test, librerías  
	- Instrumented Test
- ViewPager
	- PagerTransformer para animaciones
- Librerías de terceros para almacenamiento
	- ¿Cuáles hay? Realm, Firebase, etc.  
	- Ventajas a la persistencia local de Android
- App configuration
	- ConfigurationManager
- Patrones de arquitectura
	- MVP
	- MVC
	- MVVM
- Performance y seguridad
	- Conceptos básicos
- Manejo de multimedia
	- Video, Audio e Imágenes
- Kotlin
	- Diferencias con java  
	- Por qué usar Kotlin. Ventajas  
	- Sintaxis y semántica
- Conocimiento de librerías de 3eros
	- Glide  
	- Picasso  
	- Volley  
	- Otras
- Conectividad
	- Funcionamiento interno de Retrofit  
	- HttpUrlConnection
- Publicación en Play Store
	- Generación de APK firmados  
	- Gestión de versiones dentro de Google Play Console

# Senior

- Tests
	- UI test automation (Expresso, Appium)
- Notificaciones
	- Locales vs Push notifications (Google cloud messaging, Firebase)
- Firebase
	- Que es? Para que sirve? Integración con una android app  
	- Usos (database, push notifications, etc..)
- Performance y seguridad
	- Ofuscación de código  
	- Proguard - Dexguard  
	- Lint
- Task
	- Definición  
	- Características  
	- TaskStackBuilder  
	- TaskAffinity  
	- Task FLAGS
- DeepLink
	- Implementación y uso de wizard
- JobScheduler
	- Definición - Uso  
	- Implementación
- Sensores
	- Acelerómetro, giroscopio, campo magnético, luz, etc.
- Bluetooth
	- Manejo de intents, permisos, custom service
- Canvas
	- Dibujo en bajo nivel usando View y Surface View
- Optimización de recursos
	- Memoria, Batería
- Jetpack
	- Que es? Componentes
- Accesibilidad
	- Conceptos básicos  
	- Implementación
- AlarmManager
	- Definición  
	- Implementación
- AsyncTask
	- Memory Leaks (explicación y cómo resolverlo)
- Google maps API's
	- Integración de google maps con app  
	- Apis: geocoding, distance, etc.  
	- Google developer's console. (Crear una api key, restricciones de api key)
- Programación reactiva
	- Conceptos basicos  
	- RxJava
