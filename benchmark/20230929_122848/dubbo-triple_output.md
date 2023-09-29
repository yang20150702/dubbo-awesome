# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.167 ops/ms
# Warmup Iteration   2: 6.112 ops/ms
# Warmup Iteration   3: 8.868 ops/ms
Iteration   1: 9.247 ops/ms
Iteration   2: 9.309 ops/ms
Iteration   3: 9.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.259 ±(99.9%) 0.814 ops/ms [Average]
  (min, avg, max) = (9.222, 9.259, 9.309), stdev = 0.045
  CI (99.9%): [8.445, 10.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.482 ops/ms
# Warmup Iteration   3: 9.497 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.382 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.568 ±(99.9%) 3.303 ops/ms [Average]
  (min, avg, max) = (9.382, 9.568, 9.743), stdev = 0.181
  CI (99.9%): [6.265, 12.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 8.516 ops/ms
# Warmup Iteration   3: 9.342 ops/ms
Iteration   1: 9.181 ops/ms
Iteration   2: 9.316 ops/ms
Iteration   3: 9.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.254 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (9.181, 9.254, 9.316), stdev = 0.068
  CI (99.9%): [8.010, 10.498] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ops/ms
# Warmup Iteration   2: 7.061 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.606 ops/ms
Iteration   2: 7.711 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.706 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (7.606, 7.706, 7.799), stdev = 0.096
  CI (99.9%): [5.946, 9.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.072 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.501 ±(99.9%) 0.005 ms/op
Iteration   2: 3.507 ±(99.9%) 0.005 ms/op
Iteration   3: 3.508 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.505 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (3.501, 3.505, 3.508), stdev = 0.003
  CI (99.9%): [3.443, 3.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.227 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.004 ms/op
Iteration   2: 3.329 ±(99.9%) 0.006 ms/op
Iteration   3: 3.265 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.302 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (3.265, 3.302, 3.329), stdev = 0.033
  CI (99.9%): [2.694, 3.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.515 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.005 ms/op
Iteration   1: 3.430 ±(99.9%) 0.004 ms/op
Iteration   2: 3.467 ±(99.9%) 0.004 ms/op
Iteration   3: 3.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.430, 3.448, 3.467), stdev = 0.018
  CI (99.9%): [3.117, 3.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.997 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.006 ms/op
Iteration   1: 4.116 ±(99.9%) 0.004 ms/op
Iteration   2: 4.016 ±(99.9%) 0.007 ms/op
Iteration   3: 4.077 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.070 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (4.016, 4.070, 4.116), stdev = 0.051
  CI (99.9%): [3.144, 4.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.807 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.009 ms/op
Iteration   1: 3.522 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  19.333 ms/op
                 createUser·p0.9999: 21.216 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.553 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.056 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  21.591 ms/op
                 createUser·p0.9999: 40.756 ms/op
                 createUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271951
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266077 
    [ 5.000, 10.000) = 5226 
    [10.000, 15.000) = 302 
    [15.000, 20.000) = 116 
    [20.000, 25.000) = 195 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     40.763 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.264 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
Iteration   1: 3.331 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.583 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  19.596 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 3.406 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 24.912 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  20.062 ms/op
                 existUser·p0.9999: 25.302 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283943
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7647 
    [ 2.500,  5.000) = 271430 
    [ 5.000,  7.500) = 3981 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.616 ms/op
     p(99.9000) =     14.207 ms/op
     p(99.9900) =     24.727 ms/op
     p(99.9990) =     25.958 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.103 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.009 ms/op
Iteration   1: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 29.414 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   2: 3.489 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  22.328 ms/op
                 getUser·p0.9999: 25.942 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.466 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  19.150 ms/op
                 getUser·p0.9999: 26.560 ms/op
                 getUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274413
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4051 
    [ 2.500,  5.000) = 263820 
    [ 5.000,  7.500) = 5297 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     19.516 ms/op
     p(99.9900) =     26.644 ms/op
     p(99.9990) =     30.582 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.341 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.013 ms/op
Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.394 ms/op
                 listUser·p0.999:  20.866 ms/op
                 listUser·p0.9999: 25.047 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 4.274 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   4.157 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  15.151 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.142 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 16.421 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228363
  mean =      4.202 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 219348 
    [ 5.000,  7.500) = 6598 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 341 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     24.057 ms/op
     p(99.9990) =     25.381 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.259 ± 0.814  ops/ms
ClientPb.existUser                       thrpt       3   9.568 ± 3.303  ops/ms
ClientPb.getUser                         thrpt       3   9.254 ± 1.244  ops/ms
ClientPb.listUser                        thrpt       3   7.706 ± 1.760  ops/ms
ClientPb.createUser                       avgt       3   3.505 ± 0.063   ms/op
ClientPb.existUser                        avgt       3   3.302 ± 0.608   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 0.331   ms/op
ClientPb.listUser                         avgt       3   4.070 ± 0.925   ms/op
ClientPb.createUser                     sample  271951   3.528 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.530           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.763           ms/op
ClientPb.existUser                      sample  283943   3.376 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.616           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.727           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.017           ms/op
ClientPb.getUser                        sample  274413   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.601           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.644           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  228363   4.202 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.057           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526           ms/op
