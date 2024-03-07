# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.951 ops/ms
# Warmup Iteration   2: 12.527 ops/ms
# Warmup Iteration   3: 12.647 ops/ms
Iteration   1: 12.899 ops/ms
Iteration   2: 13.069 ops/ms
Iteration   3: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.977 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (12.899, 12.977, 13.069), stdev = 0.086
  CI (99.9%): [11.403, 14.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.226 ops/ms
# Warmup Iteration   2: 13.465 ops/ms
# Warmup Iteration   3: 13.390 ops/ms
Iteration   1: 13.482 ops/ms
Iteration   2: 13.566 ops/ms
Iteration   3: 13.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.425 ±(99.9%) 3.215 ops/ms [Average]
  (min, avg, max) = (13.227, 13.425, 13.566), stdev = 0.176
  CI (99.9%): [10.209, 16.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ops/ms
# Warmup Iteration   2: 12.805 ops/ms
# Warmup Iteration   3: 12.931 ops/ms
Iteration   1: 13.183 ops/ms
Iteration   2: 13.059 ops/ms
Iteration   3: 13.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.120 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (13.059, 13.120, 13.183), stdev = 0.062
  CI (99.9%): [11.988, 14.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.592 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 10.823 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.840 ±(99.9%) 0.821 ops/ms [Average]
  (min, avg, max) = (10.806, 10.840, 10.891), stdev = 0.045
  CI (99.9%): [10.019, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.477, 2.485, 2.492), stdev = 0.007
  CI (99.9%): [2.355, 2.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.612 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.003 ms/op
Iteration   1: 2.392 ±(99.9%) 0.003 ms/op
Iteration   2: 2.401 ±(99.9%) 0.003 ms/op
Iteration   3: 2.388 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.394 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.388, 2.394, 2.401), stdev = 0.007
  CI (99.9%): [2.273, 2.514] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.003 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.424 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.418, 2.424, 2.432), stdev = 0.007
  CI (99.9%): [2.291, 2.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.941, 2.958, 2.984), stdev = 0.023
  CI (99.9%): [2.547, 3.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.024 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  8.806 ms/op
                 createUser·p0.9999: 13.634 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   4.071 ms/op
                 createUser·p0.999:  8.866 ms/op
                 createUser·p0.9999: 11.977 ms/op
                 createUser·p1.00:   12.190 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 12.331 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384023
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187021 
    [ 2.500,  3.750) = 192459 
    [ 3.750,  5.000) = 3311 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     12.740 ms/op
     p(99.9990) =     14.382 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.399 ±(99.9%) 0.005 ms/op
Iteration   1: 2.396 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.673 ms/op
                 existUser·p0.9999: 17.891 ms/op
                 existUser·p1.00:   19.104 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  7.304 ms/op
                 existUser·p0.9999: 14.462 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 10.928 ms/op
                 existUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400581
  mean =      2.394 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 207439 
    [ 2.500,  3.750) = 190175 
    [ 3.750,  5.000) = 2069 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     14.856 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  6.061 ms/op
                 getUser·p0.9999: 14.597 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  7.480 ms/op
                 getUser·p0.9999: 12.206 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  6.736 ms/op
                 getUser·p0.9999: 11.155 ms/op
                 getUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390454
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 198292 
    [ 2.500,  3.750) = 187694 
    [ 3.750,  5.000) = 3654 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      6.831 ms/op
     p(99.9900) =     13.680 ms/op
     p(99.9990) =     14.880 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.608 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.009 ms/op
Iteration   1: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.488 ms/op
                 listUser·p0.9999: 10.224 ms/op
                 listUser·p1.00:   11.043 ms/op

Iteration   2: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.638 ms/op
                 listUser·p0.9999: 10.765 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.901 ms/op
                 listUser·p0.9999: 10.215 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323903
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 100551 
    [ 2.500,  3.750) = 187084 
    [ 3.750,  5.000) = 29532 
    [ 5.000,  6.250) = 5368 
    [ 6.250,  7.500) = 585 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      8.980 ms/op
     p(99.9900) =     10.463 ms/op
     p(99.9990) =     11.494 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.977 ± 1.574  ops/ms
ClientPb.existUser                       thrpt       3  13.425 ± 3.215  ops/ms
ClientPb.getUser                         thrpt       3  13.120 ± 1.132  ops/ms
ClientPb.listUser                        thrpt       3  10.840 ± 0.821  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.130   ms/op
ClientPb.existUser                        avgt       3   2.394 ± 0.120   ms/op
ClientPb.getUser                          avgt       3   2.424 ± 0.132   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.412   ms/op
ClientPb.createUser                     sample  384023   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.447           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.848           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.740           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  400581   2.394 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.531           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.569           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.856           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.104           ms/op
ClientPb.getUser                        sample  390454   2.457 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.707           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.172           ms/op
ClientPb.listUser                       sample  323903   2.961 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.980           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.846           ms/op
