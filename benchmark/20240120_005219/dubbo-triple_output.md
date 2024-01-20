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
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 12.001 ops/ms
# Warmup Iteration   3: 12.011 ops/ms
Iteration   1: 12.496 ops/ms
Iteration   2: 12.391 ops/ms
Iteration   3: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.476 ±(99.9%) 1.408 ops/ms [Average]
  (min, avg, max) = (12.391, 12.476, 12.542), stdev = 0.077
  CI (99.9%): [11.068, 13.884] (assumes normal distribution)


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
# Warmup Iteration   1: 8.299 ops/ms
# Warmup Iteration   2: 13.029 ops/ms
# Warmup Iteration   3: 12.912 ops/ms
Iteration   1: 13.068 ops/ms
Iteration   2: 13.147 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.094 ±(99.9%) 0.841 ops/ms [Average]
  (min, avg, max) = (13.066, 13.094, 13.147), stdev = 0.046
  CI (99.9%): [12.253, 13.935] (assumes normal distribution)


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
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 12.553 ops/ms
# Warmup Iteration   3: 12.785 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.909 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.879 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (12.804, 12.879, 12.925), stdev = 0.066
  CI (99.9%): [11.673, 14.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.904 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.664 ops/ms
Iteration   1: 10.661 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.662 ±(99.9%) 0.142 ops/ms [Average]
  (min, avg, max) = (10.655, 10.662, 10.671), stdev = 0.008
  CI (99.9%): [10.521, 10.804] (assumes normal distribution)


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.528, 2.545, 2.570), stdev = 0.022
  CI (99.9%): [2.147, 2.944] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.003 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.434, 2.440, 2.449), stdev = 0.008
  CI (99.9%): [2.297, 2.583] (assumes normal distribution)


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.530 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (2.504, 2.530, 2.549), stdev = 0.023
  CI (99.9%): [2.107, 2.952] (assumes normal distribution)


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
# Warmup Iteration   1: 4.639 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.994, 3.021, 3.053), stdev = 0.030
  CI (99.9%): [2.471, 3.570] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.683 ms/op
                 createUser·p0.999:  11.384 ms/op
                 createUser·p0.9999: 13.486 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 13.801 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 11.263 ms/op
                 createUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379714
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 182184 
    [ 2.500,  3.750) = 193361 
    [ 3.750,  5.000) = 3308 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     13.973 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.145 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.386 ms/op
                 existUser·p0.9999: 14.049 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.702 ms/op
                 existUser·p0.999:  8.508 ms/op
                 existUser·p0.9999: 12.377 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385503
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 191019 
    [ 2.500,  3.750) = 190973 
    [ 3.750,  5.000) = 2800 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.529 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     14.673 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.328 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  11.958 ms/op
                 getUser·p0.9999: 13.682 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  10.074 ms/op
                 getUser·p0.9999: 11.686 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.449 ms/op
                 getUser·p0.9999: 11.305 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387411
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 192849 
    [ 2.500,  3.750) = 189007 
    [ 3.750,  5.000) = 3920 
    [ 5.000,  6.250) = 1054 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.328 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      8.530 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     13.851 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.338 ms/op
                 listUser·p0.9999: 11.444 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  10.196 ms/op
                 listUser·p0.9999: 11.879 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.990 ms/op
                 listUser·p0.9999: 12.501 ms/op
                 listUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316978
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 87182 
    [ 2.500,  3.750) = 190720 
    [ 3.750,  5.000) = 31613 
    [ 5.000,  6.250) = 6005 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 216 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     12.195 ms/op
     p(99.9990) =     12.629 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.476 ± 1.408  ops/ms
ClientPb.existUser                       thrpt       3  13.094 ± 0.841  ops/ms
ClientPb.getUser                         thrpt       3  12.879 ± 1.206  ops/ms
ClientPb.listUser                        thrpt       3  10.662 ± 0.142  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.398   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.530 ± 0.422   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.550   ms/op
ClientPb.createUser                     sample  379714   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.819           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.648           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  385503   2.489 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.529           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  387411   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.328           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.876           ms/op
ClientPb.listUser                       sample  316978   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
