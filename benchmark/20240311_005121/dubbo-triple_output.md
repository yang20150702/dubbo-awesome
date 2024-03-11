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
# Warmup Iteration   1: 5.255 ops/ms
# Warmup Iteration   2: 12.234 ops/ms
# Warmup Iteration   3: 12.267 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.708 ops/ms
Iteration   3: 12.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.699 ±(99.9%) 0.445 ops/ms [Average]
  (min, avg, max) = (12.671, 12.699, 12.717), stdev = 0.024
  CI (99.9%): [12.253, 13.144] (assumes normal distribution)


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
# Warmup Iteration   1: 8.427 ops/ms
# Warmup Iteration   2: 13.328 ops/ms
# Warmup Iteration   3: 13.575 ops/ms
Iteration   1: 13.420 ops/ms
Iteration   2: 13.585 ops/ms
Iteration   3: 13.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.545 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (13.420, 13.545, 13.630), stdev = 0.111
  CI (99.9%): [11.526, 15.565] (assumes normal distribution)


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
# Warmup Iteration   1: 7.223 ops/ms
# Warmup Iteration   2: 12.529 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 12.786 ops/ms
Iteration   2: 13.008 ops/ms
Iteration   3: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.941 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (12.786, 12.941, 13.029), stdev = 0.134
  CI (99.9%): [10.491, 15.392] (assumes normal distribution)


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
# Warmup Iteration   1: 6.626 ops/ms
# Warmup Iteration   2: 10.577 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.609 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.622 ±(99.9%) 0.821 ops/ms [Average]
  (min, avg, max) = (10.584, 10.622, 10.671), stdev = 0.045
  CI (99.9%): [9.801, 11.442] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.477, 2.491, 2.501), stdev = 0.013
  CI (99.9%): [2.255, 2.728] (assumes normal distribution)


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.413 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.003 ms/op
Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.393, 2.411, 2.431), stdev = 0.019
  CI (99.9%): [2.068, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
Iteration   3: 2.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (2.458, 2.474, 2.502), stdev = 0.024
  CI (99.9%): [2.036, 2.913] (assumes normal distribution)


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
# Warmup Iteration   1: 4.899 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (2.989, 3.009, 3.023), stdev = 0.017
  CI (99.9%): [2.691, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  10.909 ms/op
                 createUser·p0.9999: 13.505 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  7.060 ms/op
                 createUser·p0.9999: 12.329 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.316 ms/op
                 createUser·p0.9999: 10.586 ms/op
                 createUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385127
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187312 
    [ 2.500,  3.750) = 193604 
    [ 3.750,  5.000) = 3397 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     13.033 ms/op
     p(99.9990) =     13.613 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.649 ms/op
                 existUser·p0.9999: 13.918 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.672 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.620 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 11.085 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395737
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 199126 
    [ 2.500,  3.750) = 193850 
    [ 3.750,  5.000) = 2134 
    [ 5.000,  6.250) = 198 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      6.187 ms/op
     p(99.9900) =     13.432 ms/op
     p(99.9990) =     14.420 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.741 ms/op
                 getUser·p0.9999: 16.286 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 12.619 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  6.036 ms/op
                 getUser·p0.9999: 12.008 ms/op
                 getUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390253
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 197894 
    [ 2.500,  3.750) = 187672 
    [ 3.750,  5.000) = 3785 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      6.568 ms/op
     p(99.9900) =     13.334 ms/op
     p(99.9990) =     16.397 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.680 ms/op
                 listUser·p0.9999: 10.844 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 10.535 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317208
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 89770 
    [ 2.500,  3.750) = 187144 
    [ 3.750,  5.000) = 33014 
    [ 5.000,  6.250) = 5859 
    [ 6.250,  7.500) = 680 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.090 ms/op
     p(99.9900) =     10.703 ms/op
     p(99.9990) =     11.538 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.699 ± 0.445  ops/ms
ClientPb.existUser                       thrpt       3  13.545 ± 2.019  ops/ms
ClientPb.getUser                         thrpt       3  12.941 ± 2.450  ops/ms
ClientPb.listUser                        thrpt       3  10.622 ± 0.821  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.237   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.342   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.438   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.318   ms/op
ClientPb.createUser                     sample  385127   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.815           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.308           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.033           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.582           ms/op
ClientPb.existUser                      sample  395737   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.673           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.187           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.432           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  390253   2.458 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.598           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.334           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.597           ms/op
ClientPb.listUser                       sample  317208   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.937           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.703           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.796           ms/op
