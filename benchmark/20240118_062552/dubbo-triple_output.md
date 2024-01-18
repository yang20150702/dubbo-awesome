# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.132 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.436 ops/ms
Iteration   1: 12.738 ops/ms
Iteration   2: 12.841 ops/ms
Iteration   3: 12.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.757 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (12.693, 12.757, 12.841), stdev = 0.076
  CI (99.9%): [11.377, 14.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.038 ops/ms
# Warmup Iteration   2: 13.159 ops/ms
# Warmup Iteration   3: 13.158 ops/ms
Iteration   1: 13.232 ops/ms
Iteration   2: 13.485 ops/ms
Iteration   3: 13.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.355 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (13.232, 13.355, 13.485), stdev = 0.127
  CI (99.9%): [11.047, 15.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.768 ops/ms
# Warmup Iteration   2: 12.756 ops/ms
# Warmup Iteration   3: 12.838 ops/ms
Iteration   1: 12.949 ops/ms
Iteration   2: 13.096 ops/ms
Iteration   3: 13.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.052 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (12.949, 13.052, 13.111), stdev = 0.089
  CI (99.9%): [11.419, 14.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ops/ms
# Warmup Iteration   2: 10.525 ops/ms
# Warmup Iteration   3: 10.565 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.633 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (10.599, 10.633, 10.652), stdev = 0.030
  CI (99.9%): [10.089, 11.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
Iteration   3: 2.500 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.500, 2.513, 2.536), stdev = 0.020
  CI (99.9%): [2.143, 2.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.443, 2.452, 2.468), stdev = 0.015
  CI (99.9%): [2.186, 2.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.478 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.028 ms/op [Average]
  (min, avg, max) = (2.475, 2.477, 2.478), stdev = 0.002
  CI (99.9%): [2.449, 2.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
Iteration   3: 2.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.982, 2.997, 3.013), stdev = 0.016
  CI (99.9%): [2.713, 3.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  11.822 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.441 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  9.731 ms/op
                 createUser·p0.9999: 13.255 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  9.008 ms/op
                 createUser·p0.9999: 10.916 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382407
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 193693 
    [ 2.500,  3.750) = 181467 
    [ 3.750,  5.000) = 5945 
    [ 5.000,  6.250) = 632 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      9.099 ms/op
     p(99.9900) =     13.283 ms/op
     p(99.9990) =     13.747 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  7.790 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  7.258 ms/op
                 existUser·p0.9999: 13.436 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.819 ms/op
                 existUser·p0.999:  7.609 ms/op
                 existUser·p0.9999: 11.570 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389308
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 194502 
    [ 2.500,  3.750) = 191273 
    [ 3.750,  5.000) = 2595 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.624 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  10.657 ms/op
                 getUser·p0.9999: 14.500 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  5.798 ms/op
                 getUser·p0.9999: 12.280 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.668 ms/op
                 getUser·p0.9999: 11.489 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384754
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 190797 
    [ 2.500,  3.750) = 189131 
    [ 3.750,  5.000) = 3760 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      6.744 ms/op
     p(99.9900) =     13.870 ms/op
     p(99.9990) =     15.371 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.029 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.692 ms/op
                 listUser·p0.999:  9.663 ms/op
                 listUser·p0.9999: 11.562 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.600 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 11.543 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312224
  mean =      3.072 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 80159 
    [ 2.500,  3.750) = 188326 
    [ 3.750,  5.000) = 35317 
    [ 5.000,  6.250) = 6940 
    [ 6.250,  7.500) = 699 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     11.563 ms/op
     p(99.9990) =     12.151 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.757 ± 1.380  ops/ms
ClientPb.existUser                       thrpt       3  13.355 ± 2.308  ops/ms
ClientPb.getUser                         thrpt       3  13.052 ± 1.633  ops/ms
ClientPb.listUser                        thrpt       3  10.633 ± 0.545  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.370   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.266   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.028   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.284   ms/op
ClientPb.createUser                     sample  382407   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.482           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.099           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  389308   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.624           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  384754   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.931           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.744           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  312224   3.072 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.563           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.206           ms/op
