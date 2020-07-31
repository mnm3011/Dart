#### If you're inside a Flutter Widget, you can use debugPrint
```
import 'package:flutter/foundation.dart';

debugPrint('movieTitle: $movieTitle');
```

#### Otherwise, you can use Dart's built in log function
```
import 'dart:developer';

log('data: $data');
```
