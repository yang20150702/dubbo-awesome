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
# Warmup Iteration   1: 5.111 ops/ms
# Warmup Iteration   2: 12.002 ops/ms
# Warmup Iteration   3: 12.259 ops/ms
Iteration   1: 12.458 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.520 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (12.458, 12.520, 12.569), stdev = 0.057
  CI (99.9%): [11.485, 13.554] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ops/ms
# Warmup Iteration   2: 12.907 ops/ms
# Warmup Iteration   3: 12.697 ops/ms
Iteration   1: 12.898 ops/ms
Iteration   2: 13.053 ops/ms
Iteration   3: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.954 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (12.898, 12.954, 13.053), stdev = 0.086
  CI (99.9%): [11.389, 14.520] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.587 ops/ms
# Warmup Iteration   2: 12.243 ops/ms
# Warmup Iteration   3: 12.588 ops/ms
Iteration   1: 12.634 ops/ms
Iteration   2: 12.629 ops/ms
Iteration   3: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.585 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (12.491, 12.585, 12.634), stdev = 0.081
  CI (99.9%): [11.112, 14.057] (assumes normal distribution)


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
# Warmup Iteration   1: 6.651 ops/ms
# Warmup Iteration   2: 10.331 ops/ms
# Warmup Iteration   3: 10.488 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.429 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (10.365, 10.429, 10.469), stdev = 0.055
  CI (99.9%): [9.417, 11.441] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.593 ±(99.9%) 0.004 ms/op
Iteration   1: 2.612 ±(99.9%) 0.004 ms/op
Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.587 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (2.558, 2.587, 2.612), stdev = 0.027
  CI (99.9%): [2.093, 3.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.483, 2.498, 2.509), stdev = 0.014
  CI (99.9%): [2.245, 2.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.506, 2.512, 2.525), stdev = 0.011
  CI (99.9%): [2.319, 2.706] (assumes normal distribution)


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
# Warmup Iteration   1: 4.804 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.004 ms/op
Iteration   1: 3.075 ±(99.9%) 0.005 ms/op
Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
Iteration   3: 3.053 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.058 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.047, 3.058, 3.075), stdev = 0.015
  CI (99.9%): [2.789, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 14.132 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 13.231 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.342 ms/op
                 createUser·p0.9999: 9.912 ms/op
                 createUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373647
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 177267 
    [ 2.500,  3.750) = 191759 
    [ 3.750,  5.000) = 3723 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.871 ms/op
     p(99.9990) =     14.406 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.855 ms/op
                 existUser·p0.999:  6.003 ms/op
                 existUser·p0.9999: 14.120 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  7.853 ms/op
                 existUser·p0.9999: 14.322 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.443 ms/op
                 existUser·p0.9999: 13.693 ms/op
                 existUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384286
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 186675 
    [ 2.500,  3.750) = 193166 
    [ 3.750,  5.000) = 3353 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 148 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      6.913 ms/op
     p(99.9900) =     13.985 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 13.850 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.384 ms/op
                 getUser·p0.9999: 13.058 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  8.981 ms/op
                 getUser·p0.9999: 12.049 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378939
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 185995 
    [ 2.500,  3.750) = 187452 
    [ 3.750,  5.000) = 4323 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.079 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.163 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.531 ms/op
                 listUser·p0.9999: 11.612 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.931 ms/op
                 listUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319036
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 94153 
    [ 2.500,  3.750) = 185969 
    [ 3.750,  5.000) = 31316 
    [ 5.000,  6.250) = 6038 
    [ 6.250,  7.500) = 738 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     11.804 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.520 ± 1.034  ops/ms
ClientPb.existUser                       thrpt       3  12.954 ± 1.565  ops/ms
ClientPb.getUser                         thrpt       3  12.585 ± 1.473  ops/ms
ClientPb.listUser                        thrpt       3  10.429 ± 1.012  ops/ms
ClientPb.createUser                       avgt       3   2.587 ± 0.494   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.253   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.193   ms/op
ClientPb.listUser                         avgt       3   3.058 ± 0.269   ms/op
ClientPb.createUser                     sample  373647   2.567 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  384286   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.677           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.913           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.729           ms/op
ClientPb.getUser                        sample  378939   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.742           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.079           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  319036   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
