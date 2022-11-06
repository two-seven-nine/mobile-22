# Preparing for Mobile Interview

## Android framework
  - [] ART
  - [] ART vs Dalvik
  - [] App profiles
  - [] Garbage collection

## Development

### Architecture
  - [] MVVM
  - [] MVI 
  - [] MVP
  - [] SOLID
  - [] DRY
  - [] Composition vs inheritance
  - [] Clean architecture and usecases
  - [] Modularisation

### Android Architecture Components
  - [] ViewModel (How does it work)
  - [] LiveData
  - [] Lifecycle

### Views and Rendering
  - [] Activity/Fragment/View lifecycle
  - []Activity launch modes
  - [] Intents (Explicit vs Implicit)
  - [] Data sharing between activities, fragments, viewmodels.
  - [] View rendering
  
### Lists
  - [] RecyclerView internals
  - [] DiffUtil
  - [] RecyclerView prefetching

### Images
  - [] Bitmaps
  - [] Bitmap Recycling
  - [] Image caching

### Memory
  - [] Memory allocation
  - [] Memory leaks

### IO
  - [] Concurency vs Parallelism
  - [] Multi-threading
    - Threads
    - Concurrent reads/writes
    - Handlers, HandlerThreads
    - ExecutorService, ThreadManager
    - Application process and Main thread
   
  - [] Kotlin Coroutines
    - One off events
    - Continuous events
    - Throttling in continous events
    - Cancellation policies
    - CoroutineScope, CoroutineContext, Parent Job+Child Job, CustomScopes
   
  - [] RxJava
    - Observable design patterns.

### Background Ops
  - [] Foreground services
  - [] WorkManager
    - WorkManager internals
  - [] Bound Service
  - [] Push notifications and priority

### Data synchronisation
  - [] Sync strategy
  - [] Offline first
  - [] Sync conflict strategy

### Networking
  - [] OkHttp/Retrofit
  - [] Networking without OkHttp/Retrofit
  - [] Polling vs Server Push
  - [] Websockets
  - [] Grpc (https://www.infoq.com/articles/websocket-and-http2-coexist/)
  - [] Rest
  - [] Handling server errors
  - [] Network caching
  - [] Cache headers

### Data persistence
  - [] SQLlite performance
  - [] SQLite locking (https://www.sqlite.org/lockingv3.html)
  - [] ContentProviders
  - [] Room 


## Stability
  
### Screen rendering
  - [] Time to first draw
  - [] Report fully drawn
  - [] Frame metrics API
  
### Application startup
  - [] Cold start
  - [] Warm start

### Crashing reporting/Debugging
  - [] Effectively debugging a crash

### Release
  - [] Feature flags
  - [] Release channels (alpha, beta, production)
  - [] Staged rollouts

### CI/CD
  - [] Jenkins
  - [] Github actions

### Build time
  - [] Gradle cache

## Security

### Device
  - [] Require passcode
  - [] Root detection
### Network 
	- TLS
	- SSL Pinning
	- Host verification
	- Token
	- Use SSL
  - Use network security config
  - How https works?
### Data 
	 - ContentProviders (Don't export)
	 - Encrypted files
	 - Encrypted prefs
	 - Encrypted tokens/keys
	 - SMS
	 - Store encrypted data, SQLCipher
	 - Apply signature level permissions
### Application 
	 - Code obfuscation
	 - Require 2FA
	 - Strong pincodes
	 - App State Expectations like: VPN, Custom keyboards
	 - Permissions
	 - Library
	 - WebView
	 - Dynamic code loading
	 - Implicit Intents
	 - Apply signature level permissions
### Social engineering
  
## Team
  - Code reviews & Empathy
  - Mentorship and guidance
  - Learning initiatives


## Product
  - Product metrics
  - Tracking success metrics
  - Balancing business and engineering
  


