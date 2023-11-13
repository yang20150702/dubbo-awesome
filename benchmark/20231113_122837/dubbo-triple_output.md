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
# Warmup Iteration   1: 5.018 ops/ms
# Warmup Iteration   2: 12.043 ops/ms
# Warmup Iteration   3: 12.300 ops/ms
Iteration   1: 12.599 ops/ms
Iteration   2: 12.573 ops/ms
Iteration   3: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.611 ±(99.9%) 0.826 ops/ms [Average]
  (min, avg, max) = (12.573, 12.611, 12.661), stdev = 0.045
  CI (99.9%): [11.785, 13.437] (assumes normal distribution)


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
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 13.211 ops/ms
# Warmup Iteration   3: 13.062 ops/ms
Iteration   1: 13.029 ops/ms
Iteration   2: 13.087 ops/ms
Iteration   3: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.034 ±(99.9%) 0.917 ops/ms [Average]
  (min, avg, max) = (12.987, 13.034, 13.087), stdev = 0.050
  CI (99.9%): [12.118, 13.951] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.690 ops/ms
# Warmup Iteration   2: 12.533 ops/ms
# Warmup Iteration   3: 12.616 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.811 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.803 ±(99.9%) 0.301 ops/ms [Average]
  (min, avg, max) = (12.784, 12.803, 12.814), stdev = 0.017
  CI (99.9%): [12.502, 13.104] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.351 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.515 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.486 ±(99.9%) 0.262 ops/ms [Average]
  (min, avg, max) = (10.476, 10.486, 10.502), stdev = 0.014
  CI (99.9%): [10.223, 10.748] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.003 ms/op
Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
Iteration   3: 2.563 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (2.532, 2.560, 2.585), stdev = 0.026
  CI (99.9%): [2.081, 3.040] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.450, 2.459, 2.469), stdev = 0.009
  CI (99.9%): [2.287, 2.632] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.523, 2.540, 2.558), stdev = 0.018
  CI (99.9%): [2.212, 2.867] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
Iteration   3: 3.061 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (3.041, 3.051, 3.061), stdev = 0.010
  CI (99.9%): [2.872, 3.230] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 15.487 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 11.771 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 12.804 ms/op
                 createUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375704
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 177632 
    [ 2.500,  3.750) = 193024 
    [ 3.750,  5.000) = 3980 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      9.278 ms/op
     p(99.9900) =     14.483 ms/op
     p(99.9990) =     16.273 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  6.946 ms/op
                 existUser·p0.9999: 14.026 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.844 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  8.297 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386359
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 190002 
    [ 2.500,  3.750) = 192384 
    [ 3.750,  5.000) = 3053 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.186 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  11.338 ms/op
                 getUser·p0.9999: 14.030 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.839 ms/op
                 getUser·p0.999:  9.125 ms/op
                 getUser·p0.9999: 15.837 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.109 ms/op
                 getUser·p0.9999: 10.715 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379927
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 186034 
    [ 2.500,  3.750) = 188050 
    [ 3.750,  5.000) = 4254 
    [ 5.000,  6.250) = 1015 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      8.652 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     16.620 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.669 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 12.955 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.562 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 11.717 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.440 ms/op
                 listUser·p0.9999: 10.827 ms/op
                 listUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309641
  mean =      3.097 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 77495 
    [ 2.500,  3.750) = 186204 
    [ 3.750,  5.000) = 37440 
    [ 5.000,  6.250) = 6496 
    [ 6.250,  7.500) = 1094 
    [ 7.500,  8.750) = 326 
    [ 8.750, 10.000) = 296 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     12.306 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.611 ± 0.826  ops/ms
ClientPb.existUser                       thrpt       3  13.034 ± 0.917  ops/ms
ClientPb.getUser                         thrpt       3  12.803 ± 0.301  ops/ms
ClientPb.listUser                        thrpt       3  10.486 ± 0.262  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.479   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.172   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.179   ms/op
ClientPb.createUser                     sample  375704   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.813           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.317           ms/op
ClientPb.existUser                      sample  386359   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.353           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  379927   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.859           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.652           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.172           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.007           ms/op
ClientPb.listUser                       sample  309641   3.097 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.306           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.942           ms/op
