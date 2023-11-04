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
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 5.844 ops/ms
# Warmup Iteration   3: 9.046 ops/ms
Iteration   1: 9.783 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.715 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (9.650, 9.715, 9.783), stdev = 0.067
  CI (99.9%): [8.500, 10.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ops/ms
# Warmup Iteration   2: 9.602 ops/ms
# Warmup Iteration   3: 10.349 ops/ms
Iteration   1: 10.432 ops/ms
Iteration   2: 10.334 ops/ms
Iteration   3: 10.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.318 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (10.188, 10.318, 10.432), stdev = 0.123
  CI (99.9%): [8.072, 12.564] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.146 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 10.012 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.889 ±(99.9%) 2.382 ops/ms [Average]
  (min, avg, max) = (9.752, 9.889, 10.012), stdev = 0.131
  CI (99.9%): [7.506, 12.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 7.969 ops/ms
# Warmup Iteration   3: 8.152 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.441 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (8.364, 8.441, 8.518), stdev = 0.077
  CI (99.9%): [7.034, 9.848] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.908 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.002 ms/op
Iteration   1: 3.299 ±(99.9%) 0.003 ms/op
Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.231 ±(99.9%) 1.174 ms/op [Average]
  (min, avg, max) = (3.171, 3.231, 3.299), stdev = 0.064
  CI (99.9%): [2.057, 4.406] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
Iteration   3: 3.131 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.082, 3.102, 3.131), stdev = 0.026
  CI (99.9%): [2.632, 3.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.002 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.181, 3.213, 3.239), stdev = 0.030
  CI (99.9%): [2.670, 3.755] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.003 ms/op
Iteration   1: 3.887 ±(99.9%) 0.005 ms/op
Iteration   2: 3.743 ±(99.9%) 0.008 ms/op
Iteration   3: 3.784 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.805 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.743, 3.805, 3.887), stdev = 0.074
  CI (99.9%): [2.448, 5.161] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.473 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  16.725 ms/op
                 createUser·p0.9999: 21.010 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  19.762 ms/op
                 createUser·p0.9999: 22.672 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  16.297 ms/op
                 createUser·p0.9999: 19.375 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296420
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15177 
    [ 2.500,  5.000) = 275332 
    [ 5.000,  7.500) = 4908 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.939 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  16.532 ms/op
                 existUser·p0.9999: 22.189 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  12.613 ms/op
                 existUser·p0.9999: 25.718 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.181 ms/op
                 existUser·p0.999:  8.267 ms/op
                 existUser·p0.9999: 22.872 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301745
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17603 
    [ 2.500,  5.000) = 279338 
    [ 5.000,  7.500) = 4121 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     12.645 ms/op
     p(99.9900) =     24.204 ms/op
     p(99.9990) =     26.989 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.168 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.010 ms/op
Iteration   1: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 22.181 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.167 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  20.495 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 20.389 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299976
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10495 
    [ 2.500,  5.000) = 284491 
    [ 5.000,  7.500) = 4071 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     15.253 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.170 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.010 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 24.565 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 3.846 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 15.461 ms/op
                 listUser·p1.00:   15.663 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.650 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249051
  mean =      3.850 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 241216 
    [ 5.000,  7.500) = 5961 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 508 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     19.438 ms/op
     p(99.9990) =     25.019 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.715 ± 1.215  ops/ms
ClientPb.existUser                       thrpt       3  10.318 ± 2.246  ops/ms
ClientPb.getUser                         thrpt       3   9.889 ± 2.382  ops/ms
ClientPb.listUser                        thrpt       3   8.441 ± 1.407  ops/ms
ClientPb.createUser                       avgt       3   3.231 ± 1.174   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.470   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 0.542   ms/op
ClientPb.listUser                         avgt       3   3.805 ± 1.356   ms/op
ClientPb.createUser                     sample  296420   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.003           ms/op
ClientPb.existUser                      sample  301745   3.180 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.645           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.204           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  299976   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.963           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.253           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.805           ms/op
ClientPb.listUser                       sample  249051   3.850 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.438           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
