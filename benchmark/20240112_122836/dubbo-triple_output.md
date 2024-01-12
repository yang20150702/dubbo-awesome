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
# Warmup Iteration   1: 5.066 ops/ms
# Warmup Iteration   2: 12.031 ops/ms
# Warmup Iteration   3: 12.487 ops/ms
Iteration   1: 12.638 ops/ms
Iteration   2: 12.633 ops/ms
Iteration   3: 12.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.674 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (12.633, 12.674, 12.749), stdev = 0.066
  CI (99.9%): [11.476, 13.871] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 13.001 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.172 ops/ms
Iteration   2: 12.995 ops/ms
Iteration   3: 13.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.111 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (12.995, 13.111, 13.172), stdev = 0.100
  CI (99.9%): [11.289, 14.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ops/ms
# Warmup Iteration   2: 12.811 ops/ms
# Warmup Iteration   3: 12.998 ops/ms
Iteration   1: 13.014 ops/ms
Iteration   2: 12.917 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.916 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (12.816, 12.916, 13.014), stdev = 0.099
  CI (99.9%): [11.106, 14.725] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.453 ±(99.9%) 0.633 ops/ms [Average]
  (min, avg, max) = (10.424, 10.453, 10.491), stdev = 0.035
  CI (99.9%): [9.820, 11.086] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.547 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (2.529, 2.547, 2.558), stdev = 0.016
  CI (99.9%): [2.257, 2.837] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.507 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.003 ms/op
Iteration   1: 2.431 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
Iteration   3: 2.401 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.401, 2.423, 2.437), stdev = 0.019
  CI (99.9%): [2.070, 2.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.446, 2.468, 2.484), stdev = 0.020
  CI (99.9%): [2.111, 2.824] (assumes normal distribution)


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
# Warmup Iteration   1: 5.052 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (3.002, 3.004, 3.006), stdev = 0.002
  CI (99.9%): [2.972, 3.036] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.585 ms/op
                 createUser·p0.9999: 15.286 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.441 ms/op
                 createUser·p0.999:  9.616 ms/op
                 createUser·p0.9999: 12.277 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 11.124 ms/op
                 createUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379990
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 183774 
    [ 2.500,  3.750) = 192224 
    [ 3.750,  5.000) = 2865 
    [ 5.000,  6.250) = 589 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.458 ms/op
     p(99.9900) =     13.501 ms/op
     p(99.9990) =     15.978 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  7.830 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.627 ms/op
                 existUser·p0.9999: 13.499 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  6.008 ms/op
                 existUser·p0.9999: 10.796 ms/op
                 existUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389903
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 194097 
    [ 2.500,  3.750) = 192349 
    [ 3.750,  5.000) = 2772 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.059 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.758 ms/op
                 getUser·p0.999:  6.789 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.712 ms/op
                 getUser·p0.9999: 12.079 ms/op
                 getUser·p1.00:   13.042 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  8.497 ms/op
                 getUser·p0.9999: 10.522 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382950
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 190356 
    [ 2.500,  3.750) = 186763 
    [ 3.750,  5.000) = 4110 
    [ 5.000,  6.250) = 1073 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      8.783 ms/op
     p(99.9900) =     13.591 ms/op
     p(99.9990) =     14.708 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.139 ms/op
                 listUser·p0.9999: 10.393 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.386 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 12.116 ms/op
                 listUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316797
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 88516 
    [ 2.500,  3.750) = 187149 
    [ 3.750,  5.000) = 33627 
    [ 5.000,  6.250) = 5814 
    [ 6.250,  7.500) = 780 
    [ 7.500,  8.750) = 341 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     12.362 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.674 ± 1.197  ops/ms
ClientPb.existUser                       thrpt       3  13.111 ± 1.822  ops/ms
ClientPb.getUser                         thrpt       3  12.916 ± 1.809  ops/ms
ClientPb.listUser                        thrpt       3  10.453 ± 0.633  ops/ms
ClientPb.createUser                       avgt       3   2.547 ± 0.290   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.354   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.356   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.032   ms/op
ClientPb.createUser                     sample  379990   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.483           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.458           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.501           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.155           ms/op
ClientPb.existUser                      sample  389903   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.468           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.107           ms/op
ClientPb.getUser                        sample  382950   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.888           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.783           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.591           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.828           ms/op
ClientPb.listUser                       sample  316797   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
