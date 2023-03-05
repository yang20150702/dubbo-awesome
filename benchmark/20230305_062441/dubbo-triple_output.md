# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.940 ops/ms
# Warmup Iteration   2: 4.239 ops/ms
# Warmup Iteration   3: 8.617 ops/ms
Iteration   1: 8.745 ops/ms
Iteration   2: 9.160 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.097 ±(99.9%) 5.948 ops/ms [Average]
  (min, avg, max) = (8.745, 9.097, 9.388), stdev = 0.326
  CI (99.9%): [3.150, 15.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.964 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 9.511 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.533 ±(99.9%) 5.281 ops/ms [Average]
  (min, avg, max) = (9.198, 9.533, 9.705), stdev = 0.289
  CI (99.9%): [4.252, 14.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 8.864 ops/ms
Iteration   1: 9.119 ops/ms
Iteration   2: 9.367 ops/ms
Iteration   3: 9.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.290 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (9.119, 9.290, 9.383), stdev = 0.148
  CI (99.9%): [6.585, 11.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.636 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.066 ±(99.9%) 3.156 ops/ms [Average]
  (min, avg, max) = (7.884, 8.066, 8.229), stdev = 0.173
  CI (99.9%): [4.910, 11.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.023 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.447 ±(99.9%) 0.006 ms/op
Iteration   2: 3.466 ±(99.9%) 0.012 ms/op
Iteration   3: 3.371 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.428 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.371, 3.428, 3.466), stdev = 0.050
  CI (99.9%): [2.512, 4.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.393 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
Iteration   1: 3.261 ±(99.9%) 0.004 ms/op
Iteration   2: 3.456 ±(99.9%) 0.003 ms/op
Iteration   3: 3.290 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 1.915 ms/op [Average]
  (min, avg, max) = (3.261, 3.335, 3.456), stdev = 0.105
  CI (99.9%): [1.420, 5.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.184 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.004 ms/op
Iteration   1: 3.536 ±(99.9%) 0.004 ms/op
Iteration   2: 3.442 ±(99.9%) 0.002 ms/op
Iteration   3: 3.532 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.442, 3.504, 3.536), stdev = 0.053
  CI (99.9%): [2.535, 4.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.503 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.008 ms/op
Iteration   1: 4.034 ±(99.9%) 0.010 ms/op
Iteration   2: 3.881 ±(99.9%) 0.013 ms/op
Iteration   3: 3.973 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (3.881, 3.963, 4.034), stdev = 0.077
  CI (99.9%): [2.559, 5.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.918 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.015 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  21.399 ms/op
                 createUser·p0.9999: 24.129 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.424 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  16.668 ms/op
                 createUser·p0.9999: 22.741 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287133
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16441 
    [ 2.500,  5.000) = 265906 
    [ 5.000,  7.500) = 4054 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.483 ms/op
     p(99.9900) =     23.963 ms/op
     p(99.9990) =     24.922 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  20.596 ms/op
                 existUser·p0.9999: 27.951 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  19.443 ms/op
                 existUser·p0.9999: 25.867 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  11.087 ms/op
                 existUser·p0.9999: 27.019 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289477
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14750 
    [ 2.500,  5.000) = 269911 
    [ 5.000,  7.500) = 3851 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.951 ms/op
     p(99.9900) =     27.330 ms/op
     p(99.9990) =     28.689 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.354 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.012 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  22.315 ms/op
                 getUser·p0.9999: 33.292 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 3.521 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  23.859 ms/op
                 getUser·p0.9999: 28.616 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 3.463 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274417
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5093 
    [ 2.500,  5.000) = 261245 
    [ 5.000,  7.500) = 6948 
    [ 7.500, 10.000) = 752 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     21.810 ms/op
     p(99.9900) =     31.902 ms/op
     p(99.9990) =     34.374 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.711 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.013 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  21.943 ms/op
                 listUser·p0.9999: 26.427 ms/op
                 listUser·p1.00:   27.165 ms/op

Iteration   2: 4.095 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  14.699 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237510
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 227282 
    [ 5.000,  7.500) = 7937 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     24.994 ms/op
     p(99.9990) =     27.021 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.097 ± 5.948  ops/ms
ClientPb.existUser                       thrpt       3   9.533 ± 5.281  ops/ms
ClientPb.getUser                         thrpt       3   9.290 ± 2.704  ops/ms
ClientPb.listUser                        thrpt       3   8.066 ± 3.156  ops/ms
ClientPb.createUser                       avgt       3   3.428 ± 0.916   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 1.915   ms/op
ClientPb.getUser                          avgt       3   3.504 ± 0.968   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 1.404   ms/op
ClientPb.createUser                     sample  287133   3.340 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.963           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  289477   3.315 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.468           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.951           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.330           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.901           ms/op
ClientPb.getUser                        sample  274417   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.902           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  237510   4.040 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.219           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.165           ms/op
