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
# Warmup Iteration   1: 4.772 ops/ms
# Warmup Iteration   2: 12.122 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.408 ops/ms
Iteration   2: 12.546 ops/ms
Iteration   3: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.488 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (12.408, 12.488, 12.546), stdev = 0.072
  CI (99.9%): [11.183, 13.794] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.941 ops/ms
Iteration   1: 12.757 ops/ms
Iteration   2: 12.868 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.854 ±(99.9%) 1.654 ops/ms [Average]
  (min, avg, max) = (12.757, 12.854, 12.937), stdev = 0.091
  CI (99.9%): [11.200, 14.508] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.779 ops/ms
# Warmup Iteration   2: 12.307 ops/ms
# Warmup Iteration   3: 12.595 ops/ms
Iteration   1: 12.539 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.670 ±(99.9%) 2.078 ops/ms [Average]
  (min, avg, max) = (12.539, 12.670, 12.746), stdev = 0.114
  CI (99.9%): [10.592, 14.747] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.421 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.372 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.501 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (10.422, 10.501, 10.565), stdev = 0.073
  CI (99.9%): [9.176, 11.826] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.141 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.584 ±(99.9%) 0.005 ms/op
Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
Iteration   3: 2.585 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.580 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.569, 2.580, 2.585), stdev = 0.009
  CI (99.9%): [2.419, 2.741] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.003 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.465, 2.478, 2.486), stdev = 0.011
  CI (99.9%): [2.273, 2.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.490, 2.515, 2.557), stdev = 0.037
  CI (99.9%): [1.847, 3.182] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.833 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
Iteration   3: 3.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.040 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.029, 3.040, 3.046), stdev = 0.010
  CI (99.9%): [2.864, 3.217] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.829 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 13.785 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 13.033 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 10.559 ms/op
                 createUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376052
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 180150 
    [ 2.500,  3.750) = 191147 
    [ 3.750,  5.000) = 3556 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 155 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      9.351 ms/op
     p(99.9900) =     13.605 ms/op
     p(99.9990) =     14.537 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  5.599 ms/op
                 existUser·p0.9999: 13.911 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  7.360 ms/op
                 existUser·p0.9999: 14.635 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.082 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 12.329 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383915
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 186411 
    [ 2.500,  3.750) = 193503 
    [ 3.750,  5.000) = 2912 
    [ 5.000,  6.250) = 649 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.919 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  12.588 ms/op
                 getUser·p0.9999: 14.000 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.852 ms/op
                 getUser·p0.9999: 15.258 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 11.223 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374647
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 180311 
    [ 2.500,  3.750) = 187826 
    [ 3.750,  5.000) = 5034 
    [ 5.000,  6.250) = 841 
    [ 6.250,  7.500) = 183 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     15.610 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 4.879 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.009 ms/op
Iteration   1: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.015 ms/op
                 listUser·p0.9999: 11.313 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.956 ms/op
                 listUser·p0.999:  10.090 ms/op
                 listUser·p0.9999: 11.741 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  8.764 ms/op
                 listUser·p0.9999: 11.691 ms/op
                 listUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311962
  mean =      3.074 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 83850 
    [ 2.500,  3.750) = 183751 
    [ 3.750,  5.000) = 35115 
    [ 5.000,  6.250) = 7517 
    [ 6.250,  7.500) = 903 
    [ 7.500,  8.750) = 280 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.488 ± 1.305  ops/ms
ClientPb.existUser                       thrpt       3  12.854 ± 1.654  ops/ms
ClientPb.getUser                         thrpt       3  12.670 ± 2.078  ops/ms
ClientPb.listUser                        thrpt       3  10.501 ± 1.325  ops/ms
ClientPb.createUser                       avgt       3   2.580 ± 0.161   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.206   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.668   ms/op
ClientPb.listUser                         avgt       3   3.040 ± 0.177   ms/op
ClientPb.createUser                     sample  376052   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.919           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.351           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.605           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.582           ms/op
ClientPb.existUser                      sample  383915   2.498 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.962           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  374647   2.560 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.056           ms/op
ClientPb.listUser                       sample  311962   3.074 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
