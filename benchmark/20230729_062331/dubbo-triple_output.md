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
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 4.851 ops/ms
# Warmup Iteration   3: 8.751 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.243 ±(99.9%) 3.861 ops/ms [Average]
  (min, avg, max) = (9.115, 9.243, 9.487), stdev = 0.212
  CI (99.9%): [5.382, 13.105] (assumes normal distribution)


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
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 9.974 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 9.754 ops/ms
Iteration   3: 9.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.930 ±(99.9%) 3.186 ops/ms [Average]
  (min, avg, max) = (9.754, 9.930, 10.103), stdev = 0.175
  CI (99.9%): [6.744, 13.115] (assumes normal distribution)


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
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 8.057 ops/ms
# Warmup Iteration   3: 9.079 ops/ms
Iteration   1: 9.569 ops/ms
Iteration   2: 9.494 ops/ms
Iteration   3: 9.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.502 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (9.444, 9.502, 9.569), stdev = 0.063
  CI (99.9%): [8.360, 10.644] (assumes normal distribution)


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
# Warmup Iteration   1: 2.802 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.713 ops/ms
Iteration   2: 7.885 ops/ms
Iteration   3: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.820 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (7.713, 7.820, 7.885), stdev = 0.093
  CI (99.9%): [6.124, 9.516] (assumes normal distribution)


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
# Warmup Iteration   1: 10.072 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.007 ms/op
Iteration   1: 3.423 ±(99.9%) 0.007 ms/op
Iteration   2: 3.224 ±(99.9%) 0.010 ms/op
Iteration   3: 3.276 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.308 ±(99.9%) 1.880 ms/op [Average]
  (min, avg, max) = (3.224, 3.308, 3.423), stdev = 0.103
  CI (99.9%): [1.427, 5.188] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.457 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.312 ±(99.9%) 0.003 ms/op
Iteration   2: 3.338 ±(99.9%) 0.007 ms/op
Iteration   3: 3.248 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.248, 3.299, 3.338), stdev = 0.046
  CI (99.9%): [2.457, 4.142] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.932 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.003 ms/op
Iteration   1: 3.410 ±(99.9%) 0.007 ms/op
Iteration   2: 3.437 ±(99.9%) 0.007 ms/op
Iteration   3: 3.357 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.401 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.357, 3.401, 3.437), stdev = 0.041
  CI (99.9%): [2.659, 4.144] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.343 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.012 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
Iteration   2: 3.990 ±(99.9%) 0.013 ms/op
Iteration   3: 4.157 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.990, 4.058, 4.157), stdev = 0.088
  CI (99.9%): [2.462, 5.654] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.895 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  19.848 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.376 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  21.742 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.977 ms/op
                 createUser·p0.9999: 28.671 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283485
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5152 
    [ 2.500,  5.000) = 274475 
    [ 5.000,  7.500) = 2773 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     20.039 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 8.850 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 27.138 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  11.093 ms/op
                 existUser·p0.9999: 23.222 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.800 ms/op
                 existUser·p0.9999: 27.893 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294488
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10898 
    [ 2.500,  5.000) = 277410 
    [ 5.000,  7.500) = 5222 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 8.767 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.057 ms/op
                 getUser·p0.999:  20.065 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  22.096 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.394 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  15.696 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280295
  mean =      3.424 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2456 
    [ 2.500,  5.000) = 272280 
    [ 5.000,  7.500) = 4548 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     16.281 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 11.563 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
Iteration   1: 4.106 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  21.407 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.060 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236902
  mean =      4.050 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 228563 
    [ 5.000,  7.500) = 6139 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.077 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     25.341 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.243 ± 3.861  ops/ms
ClientPb.existUser                       thrpt       3   9.930 ± 3.186  ops/ms
ClientPb.getUser                         thrpt       3   9.502 ± 1.142  ops/ms
ClientPb.listUser                        thrpt       3   7.820 ± 1.696  ops/ms
ClientPb.createUser                       avgt       3   3.308 ± 1.880   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.842   ms/op
ClientPb.getUser                          avgt       3   3.401 ± 0.743   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 1.596   ms/op
ClientPb.createUser                     sample  283485   3.383 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.165           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  294488   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.682           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.263           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  280295   3.424 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.281           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.592           ms/op
ClientPb.listUser                       sample  236902   4.050 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.077           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.411           ms/op
