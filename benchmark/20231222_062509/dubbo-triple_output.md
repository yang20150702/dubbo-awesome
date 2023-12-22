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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 12.330 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.709 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.769 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (12.709, 12.769, 12.854), stdev = 0.075
  CI (99.9%): [11.393, 14.145] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.208 ops/ms
# Warmup Iteration   2: 13.060 ops/ms
# Warmup Iteration   3: 13.073 ops/ms
Iteration   1: 13.164 ops/ms
Iteration   2: 13.063 ops/ms
Iteration   3: 13.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.089 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (13.040, 13.089, 13.164), stdev = 0.066
  CI (99.9%): [11.886, 14.293] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ops/ms
# Warmup Iteration   2: 12.733 ops/ms
# Warmup Iteration   3: 13.023 ops/ms
Iteration   1: 12.946 ops/ms
Iteration   2: 13.237 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.082 ±(99.9%) 2.673 ops/ms [Average]
  (min, avg, max) = (12.946, 13.082, 13.237), stdev = 0.147
  CI (99.9%): [10.409, 15.755] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.703 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.610 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (10.577, 10.610, 10.644), stdev = 0.033
  CI (99.9%): [9.998, 11.221] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.572 ±(99.9%) 0.003 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (2.527, 2.545, 2.572), stdev = 0.024
  CI (99.9%): [2.113, 2.978] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.003 ms/op
Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.413, 2.428, 2.454), stdev = 0.023
  CI (99.9%): [2.002, 2.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.003 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.486, 2.497, 2.505), stdev = 0.010
  CI (99.9%): [2.313, 2.681] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 2.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.992, 2.997, 3.000), stdev = 0.004
  CI (99.9%): [2.916, 3.078] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  11.770 ms/op
                 createUser·p0.9999: 13.981 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.478 ms/op
                 createUser·p0.999:  6.015 ms/op
                 createUser·p0.9999: 12.222 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  8.494 ms/op
                 createUser·p0.9999: 10.423 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385671
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 189335 
    [ 2.500,  3.750) = 193079 
    [ 3.750,  5.000) = 2549 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      9.098 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.657 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  7.380 ms/op
                 existUser·p0.9999: 22.017 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  7.953 ms/op
                 existUser·p0.9999: 13.845 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.504 ms/op
                 existUser·p0.999:  5.691 ms/op
                 existUser·p0.9999: 11.830 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389689
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194024 
    [ 2.500,  5.000) = 194840 
    [ 5.000,  7.500) = 459 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      7.008 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     22.456 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.955 ms/op
                 getUser·p0.999:  11.127 ms/op
                 getUser·p0.9999: 14.953 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.217 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  8.953 ms/op
                 getUser·p0.9999: 13.439 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  7.223 ms/op
                 getUser·p0.9999: 11.616 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385715
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 194343 
    [ 2.500,  3.750) = 186137 
    [ 3.750,  5.000) = 4084 
    [ 5.000,  6.250) = 645 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      7.878 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     15.125 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.009 ms/op
Iteration   1: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.034 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.630 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.474 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.498 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.002 ms/op
                 listUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321472
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 95473 
    [ 2.500,  3.750) = 188220 
    [ 3.750,  5.000) = 31081 
    [ 5.000,  6.250) = 5413 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.434 ms/op
     p(99.9990) =     13.037 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.769 ± 1.376  ops/ms
ClientPb.existUser                       thrpt       3  13.089 ± 1.203  ops/ms
ClientPb.getUser                         thrpt       3  13.082 ± 2.673  ops/ms
ClientPb.listUser                        thrpt       3  10.610 ± 0.611  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.433   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.184   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.081   ms/op
ClientPb.createUser                     sample  385671   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.415           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.098           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  389689   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  385715   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.752           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.877           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.188           ms/op
ClientPb.listUser                       sample  321472   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.434           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.074           ms/op
