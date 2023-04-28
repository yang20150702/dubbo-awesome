# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.080 ops/ms
# Warmup Iteration   2: 2.197 ops/ms
# Warmup Iteration   3: 4.577 ops/ms
Iteration   1: 5.540 ops/ms
Iteration   2: 5.510 ops/ms
Iteration   3: 5.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.670 ±(99.9%) 4.601 ops/ms [Average]
  (min, avg, max) = (5.510, 5.670, 5.961), stdev = 0.252
  CI (99.9%): [1.069, 10.271] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.507 ops/ms
# Warmup Iteration   2: 4.353 ops/ms
# Warmup Iteration   3: 5.820 ops/ms
Iteration   1: 6.047 ops/ms
Iteration   2: 6.391 ops/ms
Iteration   3: 6.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.184 ±(99.9%) 3.336 ops/ms [Average]
  (min, avg, max) = (6.047, 6.184, 6.391), stdev = 0.183
  CI (99.9%): [2.847, 9.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.560 ops/ms
# Warmup Iteration   2: 4.629 ops/ms
# Warmup Iteration   3: 5.711 ops/ms
Iteration   1: 5.648 ops/ms
Iteration   2: 5.579 ops/ms
Iteration   3: 5.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.715 ±(99.9%) 3.283 ops/ms [Average]
  (min, avg, max) = (5.579, 5.715, 5.919), stdev = 0.180
  CI (99.9%): [2.432, 8.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.556 ops/ms
# Warmup Iteration   2: 4.101 ops/ms
# Warmup Iteration   3: 4.823 ops/ms
Iteration   1: 5.020 ops/ms
Iteration   2: 4.994 ops/ms
Iteration   3: 4.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.998 ±(99.9%) 0.384 ops/ms [Average]
  (min, avg, max) = (4.979, 4.998, 5.020), stdev = 0.021
  CI (99.9%): [4.614, 5.382] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.476 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.215 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.009 ms/op
Iteration   1: 5.676 ±(99.9%) 0.012 ms/op
Iteration   2: 5.483 ±(99.9%) 0.015 ms/op
Iteration   3: 5.539 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.566 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (5.483, 5.566, 5.676), stdev = 0.099
  CI (99.9%): [3.751, 7.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.652 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.762 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.007 ms/op
Iteration   1: 5.249 ±(99.9%) 0.007 ms/op
Iteration   2: 5.387 ±(99.9%) 0.007 ms/op
Iteration   3: 5.076 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.237 ±(99.9%) 2.840 ms/op [Average]
  (min, avg, max) = (5.076, 5.237, 5.387), stdev = 0.156
  CI (99.9%): [2.398, 8.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.772 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.600 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.817 ±(99.9%) 0.010 ms/op
Iteration   1: 5.613 ±(99.9%) 0.008 ms/op
Iteration   2: 5.579 ±(99.9%) 0.009 ms/op
Iteration   3: 5.259 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.484 ±(99.9%) 3.568 ms/op [Average]
  (min, avg, max) = (5.259, 5.484, 5.613), stdev = 0.196
  CI (99.9%): [1.916, 9.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.671 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.858 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.139 ±(99.9%) 0.018 ms/op
Iteration   1: 6.527 ±(99.9%) 0.013 ms/op
Iteration   2: 6.202 ±(99.9%) 0.014 ms/op
Iteration   3: 6.348 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.359 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (6.202, 6.359, 6.527), stdev = 0.163
  CI (99.9%): [3.381, 9.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.299 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.103 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.168 ±(99.9%) 0.029 ms/op
Iteration   1: 5.548 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  23.712 ms/op
                 createUser·p0.9999: 32.750 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 5.385 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.576 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  25.567 ms/op
                 createUser·p0.9999: 30.411 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 5.669 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.417 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  31.608 ms/op
                 createUser·p0.9999: 35.479 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173460
  mean =      5.531 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 57770 
    [ 5.000,  7.500) = 106939 
    [ 7.500, 10.000) = 6622 
    [10.000, 12.500) = 1414 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.384 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.834 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 18.399 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 6.195 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.579 ±(99.9%) 0.021 ms/op
Iteration   1: 5.160 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.488 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 31.510 ms/op
                 existUser·p1.00:   33.030 ms/op

Iteration   2: 5.248 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.503 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 33.050 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 5.373 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.714 ms/op
                 existUser·p0.999:  29.080 ms/op
                 existUser·p0.9999: 34.081 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182436
  mean =      5.259 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 95191 
    [ 5.000,  7.500) = 79557 
    [ 7.500, 10.000) = 5763 
    [10.000, 12.500) = 1284 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     33.178 ms/op
     p(99.9990) =     35.929 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.684 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.605 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.484 ±(99.9%) 0.019 ms/op
Iteration   1: 5.638 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.996 ms/op
                 getUser·p0.95:   8.666 ms/op
                 getUser·p0.99:   14.352 ms/op
                 getUser·p0.999:  23.027 ms/op
                 getUser·p0.9999: 27.163 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 5.460 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.220 ms/op
                 getUser·p0.95:   7.143 ms/op
                 getUser·p0.99:   10.183 ms/op
                 getUser·p0.999:  14.229 ms/op
                 getUser·p0.9999: 31.134 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 5.522 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.818 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.971 ms/op
                 getUser·p0.99:   11.010 ms/op
                 getUser·p0.999:  27.364 ms/op
                 getUser·p0.9999: 33.084 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173308
  mean =      5.539 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 59048 
    [ 5.000,  7.500) = 103444 
    [ 7.500, 10.000) = 7573 
    [10.000, 12.500) = 1886 
    [12.500, 15.000) = 754 
    [15.000, 17.500) = 327 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     20.929 ms/op
     p(99.9900) =     31.043 ms/op
     p(99.9990) =     33.522 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.129 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 7.657 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.778 ±(99.9%) 0.026 ms/op
Iteration   1: 6.341 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.367 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.348 ms/op
                 listUser·p0.95:   9.031 ms/op
                 listUser·p0.99:   13.219 ms/op
                 listUser·p0.999:  28.126 ms/op
                 listUser·p0.9999: 39.384 ms/op
                 listUser·p1.00:   39.846 ms/op

Iteration   2: 6.469 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  29.229 ms/op
                 listUser·p0.9999: 35.529 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   3: 6.734 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.529 ms/op
                 listUser·p0.999:  24.804 ms/op
                 listUser·p0.9999: 28.549 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147326
  mean =      6.511 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4378 
    [ 5.000,  7.500) = 124042 
    [ 7.500, 10.000) = 13316 
    [10.000, 12.500) = 3755 
    [12.500, 15.000) = 1095 
    [15.000, 17.500) = 305 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.847 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.889 ms/op
     p(95.0000) =      9.404 ms/op
     p(99.0000) =     13.058 ms/op
     p(99.9000) =     27.908 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     39.815 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.670 ± 4.601  ops/ms
ClientPb.existUser                       thrpt       3   6.184 ± 3.336  ops/ms
ClientPb.getUser                         thrpt       3   5.715 ± 3.283  ops/ms
ClientPb.listUser                        thrpt       3   4.998 ± 0.384  ops/ms
ClientPb.createUser                       avgt       3   5.566 ± 1.815   ms/op
ClientPb.existUser                        avgt       3   5.237 ± 2.840   ms/op
ClientPb.getUser                          avgt       3   5.484 ± 3.568   ms/op
ClientPb.listUser                         avgt       3   6.359 ± 2.978   ms/op
ClientPb.createUser                     sample  173460   5.531 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.384           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.512           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.387           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.100           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  182436   5.259 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.488           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.891           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.178           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.307           ms/op
ClientPb.getUser                        sample  173308   5.539 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.747           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.929           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.043           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  147326   6.511 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.058           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.470           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.846           ms/op
