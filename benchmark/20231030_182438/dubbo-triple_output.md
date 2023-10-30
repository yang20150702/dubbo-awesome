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
# Warmup Iteration   1: 1.857 ops/ms
# Warmup Iteration   2: 5.467 ops/ms
# Warmup Iteration   3: 8.429 ops/ms
Iteration   1: 9.199 ops/ms
Iteration   2: 9.067 ops/ms
Iteration   3: 9.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.116 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (9.067, 9.116, 9.199), stdev = 0.073
  CI (99.9%): [7.787, 10.445] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.719 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 9.378 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.488 ±(99.9%) 5.558 ops/ms [Average]
  (min, avg, max) = (9.201, 9.488, 9.808), stdev = 0.305
  CI (99.9%): [3.931, 15.046] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.476 ops/ms
# Warmup Iteration   3: 8.730 ops/ms
Iteration   1: 8.847 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.054 ±(99.9%) 3.497 ops/ms [Average]
  (min, avg, max) = (8.847, 9.054, 9.225), stdev = 0.192
  CI (99.9%): [5.557, 12.550] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
# Warmup Iteration   2: 6.841 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.520 ops/ms
Iteration   2: 7.676 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.647 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (7.520, 7.647, 7.745), stdev = 0.115
  CI (99.9%): [5.540, 9.754] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.709 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.004 ms/op
Iteration   1: 3.458 ±(99.9%) 0.005 ms/op
Iteration   2: 3.505 ±(99.9%) 0.007 ms/op
Iteration   3: 3.450 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.471 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.450, 3.471, 3.505), stdev = 0.030
  CI (99.9%): [2.932, 4.010] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.266 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.003 ms/op
Iteration   1: 3.409 ±(99.9%) 0.002 ms/op
Iteration   2: 3.399 ±(99.9%) 0.003 ms/op
Iteration   3: 3.400 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.403 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (3.399, 3.403, 3.409), stdev = 0.005
  CI (99.9%): [3.302, 3.503] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.002 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.003 ms/op
Iteration   1: 3.405 ±(99.9%) 0.002 ms/op
Iteration   2: 3.504 ±(99.9%) 0.004 ms/op
Iteration   3: 3.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.461 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.405, 3.461, 3.504), stdev = 0.051
  CI (99.9%): [2.534, 4.388] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.729 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.008 ms/op
Iteration   1: 4.196 ±(99.9%) 0.006 ms/op
Iteration   2: 4.177 ±(99.9%) 0.005 ms/op
Iteration   3: 4.040 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.137 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (4.040, 4.137, 4.196), stdev = 0.085
  CI (99.9%): [2.586, 5.689] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.637 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.011 ms/op
Iteration   1: 3.567 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 22.446 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  22.999 ms/op
                 createUser·p0.9999: 26.535 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.915 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  18.865 ms/op
                 createUser·p0.9999: 32.003 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273637
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4967 
    [ 2.500,  5.000) = 263800 
    [ 5.000,  7.500) = 3952 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     17.242 ms/op
     p(99.9900) =     30.242 ms/op
     p(99.9990) =     33.137 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.253 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
Iteration   1: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  20.480 ms/op
                 existUser·p0.9999: 23.069 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.901 ms/op
                 existUser·p0.999:  22.357 ms/op
                 existUser·p0.9999: 26.194 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.466 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  13.594 ms/op
                 existUser·p0.9999: 27.018 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278782
  mean =      3.442 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5636 
    [ 2.500,  5.000) = 268613 
    [ 5.000,  7.500) = 3573 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     26.349 ms/op
     p(99.9990) =     27.581 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.805 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.015 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  20.820 ms/op
                 getUser·p0.9999: 24.113 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.474 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  23.321 ms/op
                 getUser·p0.9999: 25.978 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  13.003 ms/op
                 getUser·p0.9999: 26.110 ms/op
                 getUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275250
  mean =      3.486 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2411 
    [ 2.500,  5.000) = 267198 
    [ 5.000,  7.500) = 4509 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.984 ms/op
     p(99.9000) =     14.397 ms/op
     p(99.9900) =     25.394 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.289 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.011 ms/op
Iteration   1: 4.229 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  19.153 ms/op
                 listUser·p0.9999: 22.394 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 4.132 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.771 ms/op
                 listUser·p0.9999: 18.400 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.180 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.035 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 17.041 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229661
  mean =      4.180 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 218543 
    [ 5.000,  7.500) = 9335 
    [ 7.500, 10.000) = 984 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 327 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.116 ± 1.329  ops/ms
ClientPb.existUser                       thrpt       3   9.488 ± 5.558  ops/ms
ClientPb.getUser                         thrpt       3   9.054 ± 3.497  ops/ms
ClientPb.listUser                        thrpt       3   7.647 ± 2.107  ops/ms
ClientPb.createUser                       avgt       3   3.471 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   3.403 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   3.461 ± 0.927   ms/op
ClientPb.listUser                         avgt       3   4.137 ± 1.552   ms/op
ClientPb.createUser                     sample  273637   3.508 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.425           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.242           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  278782   3.442 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.116           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.349           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  275250   3.486 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.984           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.397           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.394           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.640           ms/op
ClientPb.listUser                       sample  229661   4.180 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.366           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.299           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
