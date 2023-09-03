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
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 8.272 ops/ms
Iteration   1: 8.947 ops/ms
Iteration   2: 9.143 ops/ms
Iteration   3: 8.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.014 ±(99.9%) 2.044 ops/ms [Average]
  (min, avg, max) = (8.947, 9.014, 9.143), stdev = 0.112
  CI (99.9%): [6.970, 11.058] (assumes normal distribution)


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
# Warmup Iteration   1: 3.725 ops/ms
# Warmup Iteration   2: 9.053 ops/ms
# Warmup Iteration   3: 9.576 ops/ms
Iteration   1: 9.633 ops/ms
Iteration   2: 9.583 ops/ms
Iteration   3: 9.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.643 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (9.583, 9.643, 9.713), stdev = 0.066
  CI (99.9%): [8.446, 10.840] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 8.231 ops/ms
# Warmup Iteration   3: 8.589 ops/ms
Iteration   1: 9.154 ops/ms
Iteration   2: 9.455 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.327 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (9.154, 9.327, 9.455), stdev = 0.155
  CI (99.9%): [6.493, 12.160] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.726 ops/ms
# Warmup Iteration   2: 6.694 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.868 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (7.851, 7.868, 7.894), stdev = 0.023
  CI (99.9%): [7.447, 8.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.223 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.005 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
Iteration   3: 3.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.505 ±(99.9%) 0.909 ms/op [Average]
  (min, avg, max) = (3.449, 3.505, 3.546), stdev = 0.050
  CI (99.9%): [2.596, 4.414] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.889 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.003 ms/op
Iteration   1: 3.394 ±(99.9%) 0.005 ms/op
Iteration   2: 3.451 ±(99.9%) 0.004 ms/op
Iteration   3: 3.439 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.428 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.394, 3.428, 3.451), stdev = 0.030
  CI (99.9%): [2.874, 3.982] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.501 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.006 ms/op
Iteration   1: 3.446 ±(99.9%) 0.006 ms/op
Iteration   2: 3.319 ±(99.9%) 0.011 ms/op
Iteration   3: 3.340 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.368 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.319, 3.368, 3.446), stdev = 0.068
  CI (99.9%): [2.120, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 10.181 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.008 ms/op
Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
Iteration   2: 4.137 ±(99.9%) 0.010 ms/op
Iteration   3: 4.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.112 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (4.074, 4.112, 4.137), stdev = 0.033
  CI (99.9%): [3.507, 4.716] (assumes normal distribution)


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
# Warmup Iteration   1: 10.867 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.015 ms/op
Iteration   1: 3.418 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  16.536 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.527 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  18.903 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 33.512 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276030
  mean =      3.477 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8167 
    [ 2.500,  5.000) = 259645 
    [ 5.000,  7.500) = 6779 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.232 ms/op
     p(99.9000) =     17.989 ms/op
     p(99.9900) =     29.366 ms/op
     p(99.9990) =     35.321 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 8.802 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
Iteration   1: 3.589 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.192 ms/op
                 existUser·p0.999:  20.972 ms/op
                 existUser·p0.9999: 24.432 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.432 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  23.092 ms/op
                 existUser·p0.9999: 27.842 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  10.740 ms/op
                 existUser·p0.9999: 28.961 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278291
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10659 
    [ 2.500,  5.000) = 259956 
    [ 5.000,  7.500) = 6242 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     12.447 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.859 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 7.786 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.012 ms/op
Iteration   1: 3.598 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  21.076 ms/op
                 getUser·p0.9999: 23.040 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  22.368 ms/op
                 getUser·p0.9999: 27.128 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 30.274 ms/op
                 getUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273509
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11863 
    [ 2.500,  5.000) = 252037 
    [ 5.000,  7.500) = 7770 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     28.529 ms/op
     p(99.9990) =     30.483 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 10.821 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.014 ms/op
Iteration   1: 4.140 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 27.248 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 4.050 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  15.397 ms/op
                 listUser·p0.9999: 16.250 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 4.180 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.159 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  15.328 ms/op
                 listUser·p0.9999: 20.395 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232802
  mean =      4.122 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 221526 
    [ 5.000,  7.500) = 7843 
    [ 7.500, 10.000) = 2268 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     25.850 ms/op
     p(99.9990) =     27.940 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.014 ± 2.044  ops/ms
ClientPb.existUser                       thrpt       3   9.643 ± 1.197  ops/ms
ClientPb.getUser                         thrpt       3   9.327 ± 2.833  ops/ms
ClientPb.listUser                        thrpt       3   7.868 ± 0.421  ops/ms
ClientPb.createUser                       avgt       3   3.505 ± 0.909   ms/op
ClientPb.existUser                        avgt       3   3.428 ± 0.554   ms/op
ClientPb.getUser                          avgt       3   3.368 ± 1.248   ms/op
ClientPb.listUser                         avgt       3   4.112 ± 0.604   ms/op
ClientPb.createUser                     sample  276030   3.477 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.715           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.232           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.989           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.366           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  278291   3.450 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.436           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.447           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.787           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  273509   3.506 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.529           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.605           ms/op
ClientPb.listUser                       sample  232802   4.122 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.101           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.850           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
