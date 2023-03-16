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
# Warmup Iteration   1: 2.391 ops/ms
# Warmup Iteration   2: 6.400 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.936 ±(99.9%) 2.620 ops/ms [Average]
  (min, avg, max) = (9.819, 9.936, 10.096), stdev = 0.144
  CI (99.9%): [7.316, 12.556] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ops/ms
# Warmup Iteration   2: 9.431 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.869 ops/ms
Iteration   2: 10.067 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.455 ±(99.9%) 7.329 ops/ms [Average]
  (min, avg, max) = (10.067, 10.455, 10.869), stdev = 0.402
  CI (99.9%): [3.126, 17.784] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 9.436 ops/ms
# Warmup Iteration   3: 9.436 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.105 ±(99.9%) 3.677 ops/ms [Average]
  (min, avg, max) = (9.942, 10.105, 10.330), stdev = 0.202
  CI (99.9%): [6.428, 13.781] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 7.734 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.658 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.603 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (8.547, 8.603, 8.658), stdev = 0.056
  CI (99.9%): [7.591, 9.616] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.031 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.005 ms/op
Iteration   1: 3.245 ±(99.9%) 0.008 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.118 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.157 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (3.109, 3.157, 3.245), stdev = 0.076
  CI (99.9%): [1.772, 4.542] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.094 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.017 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (2.985, 3.017, 3.038), stdev = 0.028
  CI (99.9%): [2.506, 3.528] (assumes normal distribution)


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
# Warmup Iteration   1: 7.224 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.008 ms/op
Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.145 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.094, 3.145, 3.186), stdev = 0.047
  CI (99.9%): [2.289, 4.000] (assumes normal distribution)


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
# Warmup Iteration   1: 8.652 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.006 ms/op
Iteration   1: 3.895 ±(99.9%) 0.004 ms/op
Iteration   2: 3.782 ±(99.9%) 0.005 ms/op
Iteration   3: 3.747 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.808 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.747, 3.808, 3.895), stdev = 0.077
  CI (99.9%): [2.396, 5.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  16.432 ms/op
                 createUser·p0.9999: 24.278 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.380 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  10.846 ms/op
                 createUser·p0.9999: 21.450 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.491 ms/op
                 createUser·p0.999:  13.821 ms/op
                 createUser·p0.9999: 17.540 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295100
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26666 
    [ 2.500,  5.000) = 260425 
    [ 5.000,  7.500) = 7278 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.380 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     22.659 ms/op
     p(99.9990) =     24.646 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 6.691 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.009 ms/op
Iteration   1: 3.171 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.843 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  7.876 ms/op
                 existUser·p0.9999: 21.980 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304604
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27920 
    [ 2.500,  5.000) = 271353 
    [ 5.000,  7.500) = 4698 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     33.096 ms/op
     p(99.9990) =     34.516 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 8.571 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
Iteration   1: 3.364 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  11.010 ms/op
                 getUser·p0.9999: 19.890 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 3.250 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  20.267 ms/op
                 getUser·p0.9999: 24.188 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.445 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291851
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17022 
    [ 2.500,  5.000) = 265935 
    [ 5.000,  7.500) = 8025 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     14.816 ms/op
     p(99.9900) =     22.106 ms/op
     p(99.9990) =     24.450 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 10.658 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.012 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.080 ms/op
                 listUser·p0.99:   6.429 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 21.670 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 3.772 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.640 ms/op
                 listUser·p0.9999: 16.681 ms/op
                 listUser·p1.00:   38.994 ms/op

Iteration   3: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  12.865 ms/op
                 listUser·p0.9999: 14.320 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255972
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 248540 
    [ 5.000,  7.500) = 5826 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     19.511 ms/op
     p(99.9990) =     22.035 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.936 ± 2.620  ops/ms
ClientPb.existUser                       thrpt       3  10.455 ± 7.329  ops/ms
ClientPb.getUser                         thrpt       3  10.105 ± 3.677  ops/ms
ClientPb.listUser                        thrpt       3   8.603 ± 1.013  ops/ms
ClientPb.createUser                       avgt       3   3.157 ± 1.385   ms/op
ClientPb.existUser                        avgt       3   3.017 ± 0.511   ms/op
ClientPb.getUser                          avgt       3   3.145 ± 0.855   ms/op
ClientPb.listUser                         avgt       3   3.808 ± 1.412   ms/op
ClientPb.createUser                     sample  295100   3.253 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.659           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  304604   3.148 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.830           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.096           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  291851   3.288 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.598           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.816           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.106           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.642           ms/op
ClientPb.listUser                       sample  255972   3.744 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.073           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.511           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.994           ms/op
