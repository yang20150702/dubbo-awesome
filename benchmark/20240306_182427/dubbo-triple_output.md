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
# Warmup Iteration   1: 5.137 ops/ms
# Warmup Iteration   2: 12.006 ops/ms
# Warmup Iteration   3: 12.546 ops/ms
Iteration   1: 12.610 ops/ms
Iteration   2: 12.770 ops/ms
Iteration   3: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.706 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (12.610, 12.706, 12.770), stdev = 0.085
  CI (99.9%): [11.150, 14.263] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.582 ops/ms
# Warmup Iteration   2: 13.053 ops/ms
# Warmup Iteration   3: 13.193 ops/ms
Iteration   1: 13.343 ops/ms
Iteration   2: 13.287 ops/ms
Iteration   3: 13.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 2.481 ops/ms [Average]
  (min, avg, max) = (13.084, 13.238, 13.343), stdev = 0.136
  CI (99.9%): [10.757, 15.719] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.416 ops/ms
# Warmup Iteration   2: 12.742 ops/ms
# Warmup Iteration   3: 12.896 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 12.867 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.946 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (12.867, 12.946, 13.057), stdev = 0.099
  CI (99.9%): [11.137, 14.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.745 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.668 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (10.641, 10.668, 10.684), stdev = 0.024
  CI (99.9%): [10.230, 11.107] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.482, 2.499, 2.518), stdev = 0.018
  CI (99.9%): [2.165, 2.833] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.457, 2.467, 2.485), stdev = 0.016
  CI (99.9%): [2.181, 2.752] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.484, 2.495, 2.508), stdev = 0.012
  CI (99.9%): [2.275, 2.716] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.671 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.029, 3.036, 3.042), stdev = 0.007
  CI (99.9%): [2.908, 3.163] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 13.873 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.458 ms/op
                 createUser·p0.9999: 12.337 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  9.671 ms/op
                 createUser·p0.9999: 12.570 ms/op
                 createUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378196
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 181647 
    [ 2.500,  3.750) = 192393 
    [ 3.750,  5.000) = 3190 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.644 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.248 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.577 ms/op
                 existUser·p0.999:  6.850 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  10.174 ms/op
                 existUser·p0.9999: 13.322 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.004 ms/op
                 existUser·p0.9999: 10.438 ms/op
                 existUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388288
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193641 
    [ 2.500,  5.000) = 193273 
    [ 5.000,  7.500) = 979 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.098 ms/op
     p(99.9900) =     14.306 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   2.550 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  5.775 ms/op
                 getUser·p0.9999: 17.971 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 2.587 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.177 ms/op
                 getUser·p0.95:   3.404 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 14.057 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  9.814 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374894
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 180010 
    [ 2.500,  3.750) = 188181 
    [ 3.750,  5.000) = 5377 
    [ 5.000,  6.250) = 862 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.093 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.009 ms/op
Iteration   1: 3.073 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.292 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.786 ms/op
                 listUser·p0.9999: 11.394 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.690 ms/op
                 listUser·p0.9999: 13.788 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314323
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 84304 
    [ 2.500,  3.750) = 188456 
    [ 3.750,  5.000) = 33602 
    [ 5.000,  6.250) = 6387 
    [ 6.250,  7.500) = 721 
    [ 7.500,  8.750) = 266 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.829 ms/op
     p(99.9990) =     13.859 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.706 ± 1.556  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 2.481  ops/ms
ClientPb.getUser                         thrpt       3  12.946 ± 1.809  ops/ms
ClientPb.listUser                        thrpt       3  10.668 ± 0.438  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.286   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.127   ms/op
ClientPb.createUser                     sample  378196   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.762           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  388288   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.098           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.306           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.414           ms/op
ClientPb.getUser                        sample  374894   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.860           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.842           ms/op
ClientPb.listUser                       sample  314323   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.764           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
