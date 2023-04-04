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
# Warmup Iteration   1: 1.659 ops/ms
# Warmup Iteration   2: 4.368 ops/ms
# Warmup Iteration   3: 8.503 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.883 ±(99.9%) 6.230 ops/ms [Average]
  (min, avg, max) = (8.608, 8.883, 9.265), stdev = 0.341
  CI (99.9%): [2.653, 15.113] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.465 ops/ms
# Warmup Iteration   2: 8.078 ops/ms
# Warmup Iteration   3: 9.073 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.656 ops/ms
Iteration   3: 9.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.655 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (9.624, 9.655, 9.685), stdev = 0.031
  CI (99.9%): [9.092, 10.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.438 ops/ms
# Warmup Iteration   2: 7.199 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.132 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.249 ±(99.9%) 1.891 ops/ms [Average]
  (min, avg, max) = (9.132, 9.249, 9.330), stdev = 0.104
  CI (99.9%): [7.358, 11.140] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.448 ops/ms
# Warmup Iteration   2: 6.724 ops/ms
# Warmup Iteration   3: 7.507 ops/ms
Iteration   1: 7.730 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.973 ±(99.9%) 3.936 ops/ms [Average]
  (min, avg, max) = (7.730, 7.973, 8.143), stdev = 0.216
  CI (99.9%): [4.036, 11.909] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.935 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.002 ms/op
Iteration   1: 3.556 ±(99.9%) 0.006 ms/op
Iteration   2: 3.452 ±(99.9%) 0.006 ms/op
Iteration   3: 3.458 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.488 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.452, 3.488, 3.556), stdev = 0.058
  CI (99.9%): [2.427, 4.550] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.542 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.005 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
Iteration   2: 3.338 ±(99.9%) 0.006 ms/op
Iteration   3: 3.550 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.421 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (3.338, 3.421, 3.550), stdev = 0.113
  CI (99.9%): [1.359, 5.484] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.324 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.005 ms/op
Iteration   1: 3.711 ±(99.9%) 0.005 ms/op
Iteration   2: 3.399 ±(99.9%) 0.004 ms/op
Iteration   3: 3.690 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.600 ±(99.9%) 3.176 ms/op [Average]
  (min, avg, max) = (3.399, 3.600, 3.711), stdev = 0.174
  CI (99.9%): [0.424, 6.776] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.080 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.006 ms/op
Iteration   1: 4.178 ±(99.9%) 0.008 ms/op
Iteration   2: 4.101 ±(99.9%) 0.015 ms/op
Iteration   3: 4.170 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.150 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (4.101, 4.150, 4.178), stdev = 0.042
  CI (99.9%): [3.379, 4.920] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.522 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.016 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 26.821 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   2: 3.542 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.056 ms/op
                 createUser·p0.999:  22.527 ms/op
                 createUser·p0.9999: 25.820 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  22.417 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274492
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5835 
    [ 2.500,  5.000) = 260642 
    [ 5.000,  7.500) = 6770 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 101 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.008 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.033 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  10.854 ms/op
                 existUser·p0.9999: 28.811 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  22.930 ms/op
                 existUser·p0.9999: 33.175 ms/op
                 existUser·p1.00:   33.489 ms/op

Iteration   3: 3.358 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  24.449 ms/op
                 existUser·p0.9999: 30.343 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288352
  mean =      3.326 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15512 
    [ 2.500,  5.000) = 267824 
    [ 5.000,  7.500) = 4028 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     15.083 ms/op
     p(99.9900) =     31.594 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.026 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.012 ms/op
Iteration   1: 3.468 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   7.033 ms/op
                 getUser·p0.999:  22.096 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.044 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  11.589 ms/op
                 getUser·p0.9999: 29.693 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   3: 3.600 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  21.695 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274073
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3734 
    [ 2.500,  5.000) = 260932 
    [ 5.000,  7.500) = 7556 
    [ 7.500, 10.000) = 1338 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     20.347 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.679 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.897 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.016 ms/op
Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  22.622 ms/op
                 listUser·p0.9999: 24.848 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.004 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.035 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  17.388 ms/op
                 listUser·p0.9999: 19.139 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237672
  mean =      4.041 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 228111 
    [ 5.000,  7.500) = 7245 
    [ 7.500, 10.000) = 1590 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.034 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     17.902 ms/op
     p(99.9900) =     23.903 ms/op
     p(99.9990) =     25.288 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.883 ± 6.230  ops/ms
ClientPb.existUser                       thrpt       3   9.655 ± 0.563  ops/ms
ClientPb.getUser                         thrpt       3   9.249 ± 1.891  ops/ms
ClientPb.listUser                        thrpt       3   7.973 ± 3.936  ops/ms
ClientPb.createUser                       avgt       3   3.488 ± 1.062   ms/op
ClientPb.existUser                        avgt       3   3.421 ± 2.063   ms/op
ClientPb.getUser                          avgt       3   3.600 ± 3.176   ms/op
ClientPb.listUser                         avgt       3   4.150 ± 0.770   ms/op
ClientPb.createUser                     sample  274492   3.495 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.417           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.594           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  288352   3.326 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.186           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.083           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.594           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.489           ms/op
ClientPb.getUser                        sample  274073   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.020           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  237672   4.041 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.034           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.902           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
