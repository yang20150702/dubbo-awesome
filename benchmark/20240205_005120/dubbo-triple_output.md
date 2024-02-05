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
# Warmup Iteration   1: 5.096 ops/ms
# Warmup Iteration   2: 12.078 ops/ms
# Warmup Iteration   3: 12.593 ops/ms
Iteration   1: 13.036 ops/ms
Iteration   2: 12.775 ops/ms
Iteration   3: 12.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.782 ±(99.9%) 4.560 ops/ms [Average]
  (min, avg, max) = (12.536, 12.782, 13.036), stdev = 0.250
  CI (99.9%): [8.223, 17.342] (assumes normal distribution)


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
# Warmup Iteration   1: 8.657 ops/ms
# Warmup Iteration   2: 13.812 ops/ms
# Warmup Iteration   3: 13.470 ops/ms
Iteration   1: 13.360 ops/ms
Iteration   2: 13.421 ops/ms
Iteration   3: 13.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.413 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (13.360, 13.413, 13.459), stdev = 0.050
  CI (99.9%): [12.505, 14.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ops/ms
# Warmup Iteration   2: 12.573 ops/ms
# Warmup Iteration   3: 13.076 ops/ms
Iteration   1: 13.081 ops/ms
Iteration   2: 12.958 ops/ms
Iteration   3: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.046 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (12.958, 13.046, 13.098), stdev = 0.077
  CI (99.9%): [11.647, 14.444] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 10.855 ops/ms
# Warmup Iteration   3: 11.067 ops/ms
Iteration   1: 11.151 ops/ms
Iteration   2: 11.217 ops/ms
Iteration   3: 10.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.122 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (10.998, 11.122, 11.217), stdev = 0.112
  CI (99.9%): [9.075, 13.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.003 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (2.475, 2.499, 2.524), stdev = 0.025
  CI (99.9%): [2.048, 2.950] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.426, 2.432, 2.444), stdev = 0.010
  CI (99.9%): [2.250, 2.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.439 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.428, 2.439, 2.448), stdev = 0.010
  CI (99.9%): [2.248, 2.629] (assumes normal distribution)


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
Iteration   3: 2.978 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.978, 2.987, 2.996), stdev = 0.009
  CI (99.9%): [2.823, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.276 ms/op
                 createUser·p0.9999: 13.520 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 12.445 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.996 ms/op
                 createUser·p0.9999: 11.213 ms/op
                 createUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385006
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 187060 
    [ 2.500,  3.750) = 194319 
    [ 3.750,  5.000) = 2618 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.067 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  6.090 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  7.236 ms/op
                 existUser·p0.9999: 11.996 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 11.384 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397637
  mean =      2.412 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 200091 
    [ 2.500,  3.750) = 194260 
    [ 3.750,  5.000) = 2019 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.130 ms/op
     p(99.9900) =     13.013 ms/op
     p(99.9990) =     14.058 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.050 ms/op
                 getUser·p0.9999: 13.469 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 21.374 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.015 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 12.391 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385180
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192047 
    [ 2.500,  5.000) = 191691 
    [ 5.000,  7.500) = 1046 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      8.068 ms/op
     p(99.9900) =     14.541 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.665 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.222 ms/op
                 listUser·p0.9999: 11.652 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 14.259 ms/op
                 listUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320224
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 93241 
    [ 2.500,  3.750) = 189110 
    [ 3.750,  5.000) = 30918 
    [ 5.000,  6.250) = 5491 
    [ 6.250,  7.500) = 669 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 188 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     13.198 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.782 ± 4.560  ops/ms
ClientPb.existUser                       thrpt       3  13.413 ± 0.908  ops/ms
ClientPb.getUser                         thrpt       3  13.046 ± 1.399  ops/ms
ClientPb.listUser                        thrpt       3  11.122 ± 2.047  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.451   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.182   ms/op
ClientPb.getUser                          avgt       3   2.439 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.165   ms/op
ClientPb.createUser                     sample  385006   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.960           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  397637   2.412 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.130           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  385180   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.671           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.955           ms/op
ClientPb.listUser                       sample  320224   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.198           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.991           ms/op
