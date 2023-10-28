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
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 5.420 ops/ms
# Warmup Iteration   3: 8.558 ops/ms
Iteration   1: 8.954 ops/ms
Iteration   2: 8.843 ops/ms
Iteration   3: 9.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.950 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (8.843, 8.950, 9.054), stdev = 0.105
  CI (99.9%): [7.026, 10.874] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.599 ops/ms
# Warmup Iteration   2: 8.175 ops/ms
# Warmup Iteration   3: 9.534 ops/ms
Iteration   1: 9.294 ops/ms
Iteration   2: 9.432 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.425 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (9.294, 9.425, 9.548), stdev = 0.127
  CI (99.9%): [7.100, 11.749] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 8.230 ops/ms
# Warmup Iteration   3: 8.981 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.186 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (9.050, 9.186, 9.268), stdev = 0.118
  CI (99.9%): [7.028, 11.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 7.219 ops/ms
# Warmup Iteration   3: 7.480 ops/ms
Iteration   1: 7.676 ops/ms
Iteration   2: 7.896 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.784 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (7.676, 7.784, 7.896), stdev = 0.110
  CI (99.9%): [5.773, 9.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.199 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.006 ms/op
Iteration   1: 3.519 ±(99.9%) 0.004 ms/op
Iteration   2: 3.462 ±(99.9%) 0.010 ms/op
Iteration   3: 3.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.488 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (3.462, 3.488, 3.519), stdev = 0.029
  CI (99.9%): [2.962, 4.014] (assumes normal distribution)


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
# Warmup Iteration   1: 8.738 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.006 ms/op
Iteration   1: 3.357 ±(99.9%) 0.004 ms/op
Iteration   2: 3.312 ±(99.9%) 0.002 ms/op
Iteration   3: 3.340 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.336 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.312, 3.336, 3.357), stdev = 0.023
  CI (99.9%): [2.915, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 9.538 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.004 ms/op
Iteration   1: 3.577 ±(99.9%) 0.003 ms/op
Iteration   2: 3.436 ±(99.9%) 0.005 ms/op
Iteration   3: 3.451 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.488 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.436, 3.488, 3.577), stdev = 0.077
  CI (99.9%): [2.076, 4.900] (assumes normal distribution)


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
# Warmup Iteration   1: 11.453 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.011 ms/op
Iteration   1: 4.203 ±(99.9%) 0.005 ms/op
Iteration   2: 4.144 ±(99.9%) 0.007 ms/op
Iteration   3: 4.152 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.166 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (4.144, 4.166, 4.203), stdev = 0.032
  CI (99.9%): [3.577, 4.756] (assumes normal distribution)


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
# Warmup Iteration   1: 10.673 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.013 ms/op
Iteration   1: 3.564 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.478 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  21.809 ms/op
                 createUser·p0.9999: 24.511 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.490 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  22.128 ms/op
                 createUser·p0.9999: 26.105 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 3.573 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.332 ms/op
                 createUser·p0.99:   6.352 ms/op
                 createUser·p0.999:  20.319 ms/op
                 createUser·p0.9999: 27.723 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270886
  mean =      3.542 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5059 
    [ 2.500,  5.000) = 258979 
    [ 5.000,  7.500) = 5468 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     20.549 ms/op
     p(99.9900) =     26.995 ms/op
     p(99.9990) =     28.477 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 8.465 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.009 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  11.498 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283275
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7019 
    [ 2.500,  5.000) = 270666 
    [ 5.000,  7.500) = 4524 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     11.909 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     29.169 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 10.858 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.009 ms/op
Iteration   1: 3.524 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  19.209 ms/op
                 getUser·p0.9999: 21.854 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.542 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.154 ms/op
                 getUser·p0.9999: 23.625 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  20.868 ms/op
                 getUser·p0.9999: 26.586 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273258
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3246 
    [ 2.500,  5.000) = 263101 
    [ 5.000,  7.500) = 5037 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.622 ms/op
     p(99.9000) =     19.611 ms/op
     p(99.9900) =     25.570 ms/op
     p(99.9990) =     27.465 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 11.535 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.013 ms/op
Iteration   1: 4.322 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   7.993 ms/op
                 listUser·p0.999:  21.043 ms/op
                 listUser·p0.9999: 28.180 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 4.153 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.172 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 4.147 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227992
  mean =      4.206 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 218051 
    [ 5.000,  7.500) = 7845 
    [ 7.500, 10.000) = 1184 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 283 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     26.326 ms/op
     p(99.9990) =     29.040 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.950 ± 1.924  ops/ms
ClientPb.existUser                       thrpt       3   9.425 ± 2.324  ops/ms
ClientPb.getUser                         thrpt       3   9.186 ± 2.158  ops/ms
ClientPb.listUser                        thrpt       3   7.784 ± 2.011  ops/ms
ClientPb.createUser                       avgt       3   3.488 ± 0.526   ms/op
ClientPb.existUser                        avgt       3   3.336 ± 0.422   ms/op
ClientPb.getUser                          avgt       3   3.488 ± 1.412   ms/op
ClientPb.listUser                         avgt       3   4.166 ± 0.590   ms/op
ClientPb.createUser                     sample  270886   3.542 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.549           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.995           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  283275   3.387 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.909           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.917           ms/op
ClientPb.getUser                        sample  273258   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.746           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.622           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.611           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.570           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  227992   4.206 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.597           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.326           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.491           ms/op
