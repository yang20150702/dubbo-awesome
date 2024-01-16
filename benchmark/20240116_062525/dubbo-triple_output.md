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
# Warmup Iteration   1: 4.572 ops/ms
# Warmup Iteration   2: 11.994 ops/ms
# Warmup Iteration   3: 12.347 ops/ms
Iteration   1: 12.445 ops/ms
Iteration   2: 12.602 ops/ms
Iteration   3: 12.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.604 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (12.445, 12.604, 12.767), stdev = 0.161
  CI (99.9%): [9.670, 15.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.374 ops/ms
# Warmup Iteration   2: 13.088 ops/ms
# Warmup Iteration   3: 13.170 ops/ms
Iteration   1: 13.155 ops/ms
Iteration   2: 13.247 ops/ms
Iteration   3: 13.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.232 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (13.155, 13.232, 13.294), stdev = 0.071
  CI (99.9%): [11.940, 14.524] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.543 ops/ms
# Warmup Iteration   2: 12.861 ops/ms
# Warmup Iteration   3: 13.029 ops/ms
Iteration   1: 13.039 ops/ms
Iteration   2: 13.236 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.126 ±(99.9%) 1.838 ops/ms [Average]
  (min, avg, max) = (13.039, 13.126, 13.236), stdev = 0.101
  CI (99.9%): [11.287, 14.964] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.486 ops/ms
Iteration   1: 10.598 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.583 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (10.547, 10.583, 10.604), stdev = 0.031
  CI (99.9%): [10.013, 11.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.474 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.451, 2.474, 2.508), stdev = 0.030
  CI (99.9%): [1.922, 3.025] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.053 ms/op [Average]
  (min, avg, max) = (2.450, 2.453, 2.456), stdev = 0.003
  CI (99.9%): [2.400, 2.506] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.454, 2.471, 2.487), stdev = 0.016
  CI (99.9%): [2.170, 2.771] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
Iteration   3: 2.989 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.989, 2.996, 3.000), stdev = 0.006
  CI (99.9%): [2.886, 3.106] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  11.152 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  9.112 ms/op
                 createUser·p0.9999: 12.128 ms/op
                 createUser·p1.00:   13.255 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  7.939 ms/op
                 createUser·p0.9999: 11.633 ms/op
                 createUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380351
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182245 
    [ 2.500,  5.000) = 197327 
    [ 5.000,  7.500) = 394 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.616 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     18.638 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.416 ms/op
                 existUser·p0.999:  10.473 ms/op
                 existUser·p0.9999: 14.877 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  5.778 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.644 ms/op
                 existUser·p0.9999: 15.665 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389613
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 188591 
    [ 2.500,  3.750) = 198624 
    [ 3.750,  5.000) = 1755 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.461 ms/op
     p(99.9000) =      6.109 ms/op
     p(99.9900) =     14.861 ms/op
     p(99.9990) =     16.046 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  8.697 ms/op
                 getUser·p0.9999: 13.847 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  8.029 ms/op
                 getUser·p0.9999: 13.405 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  8.313 ms/op
                 getUser·p0.9999: 12.914 ms/op
                 getUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384585
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 190035 
    [ 2.500,  3.750) = 189770 
    [ 3.750,  5.000) = 3671 
    [ 5.000,  6.250) = 638 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      7.732 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.550 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.634 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.194 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.458 ms/op
                 listUser·p0.9999: 11.340 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.559 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315891
  mean =      3.036 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 87559 
    [ 2.500,  3.750) = 187118 
    [ 3.750,  5.000) = 33567 
    [ 5.000,  6.250) = 6231 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 237 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.604 ± 2.935  ops/ms
ClientPb.existUser                       thrpt       3  13.232 ± 1.292  ops/ms
ClientPb.getUser                         thrpt       3  13.126 ± 1.838  ops/ms
ClientPb.listUser                        thrpt       3  10.583 ± 0.570  ops/ms
ClientPb.createUser                       avgt       3   2.474 ± 0.551   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.053   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.300   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.110   ms/op
ClientPb.createUser                     sample  380351   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.616           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.382           ms/op
ClientPb.existUser                      sample  389613   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.780           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.109           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.861           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.039           ms/op
ClientPb.getUser                        sample  384585   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.793           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.732           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  315891   3.036 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.899           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.550           ms/op
