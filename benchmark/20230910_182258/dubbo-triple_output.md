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
# Warmup Iteration   1: 1.236 ops/ms
# Warmup Iteration   2: 2.794 ops/ms
# Warmup Iteration   3: 5.753 ops/ms
Iteration   1: 6.112 ops/ms
Iteration   2: 6.251 ops/ms
Iteration   3: 6.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.242 ±(99.9%) 2.293 ops/ms [Average]
  (min, avg, max) = (6.112, 6.242, 6.362), stdev = 0.126
  CI (99.9%): [3.948, 8.535] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.926 ops/ms
# Warmup Iteration   2: 5.844 ops/ms
# Warmup Iteration   3: 6.418 ops/ms
Iteration   1: 6.797 ops/ms
Iteration   2: 6.457 ops/ms
Iteration   3: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.610 ±(99.9%) 3.147 ops/ms [Average]
  (min, avg, max) = (6.457, 6.610, 6.797), stdev = 0.172
  CI (99.9%): [3.463, 9.757] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.560 ops/ms
# Warmup Iteration   2: 4.784 ops/ms
# Warmup Iteration   3: 5.855 ops/ms
Iteration   1: 5.535 ops/ms
Iteration   2: 5.655 ops/ms
Iteration   3: 6.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.760 ±(99.9%) 5.345 ops/ms [Average]
  (min, avg, max) = (5.535, 5.760, 6.091), stdev = 0.293
  CI (99.9%): [0.415, 11.105] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.554 ops/ms
# Warmup Iteration   2: 4.487 ops/ms
# Warmup Iteration   3: 4.916 ops/ms
Iteration   1: 5.154 ops/ms
Iteration   2: 5.253 ops/ms
Iteration   3: 5.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.140 ±(99.9%) 2.218 ops/ms [Average]
  (min, avg, max) = (5.012, 5.140, 5.253), stdev = 0.122
  CI (99.9%): [2.922, 7.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.186 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.243 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.907 ±(99.9%) 0.008 ms/op
Iteration   1: 5.410 ±(99.9%) 0.010 ms/op
Iteration   2: 5.551 ±(99.9%) 0.012 ms/op
Iteration   3: 5.220 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.394 ±(99.9%) 3.035 ms/op [Average]
  (min, avg, max) = (5.220, 5.394, 5.551), stdev = 0.166
  CI (99.9%): [2.359, 8.429] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.548 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.008 ms/op
Iteration   1: 5.154 ±(99.9%) 0.011 ms/op
Iteration   2: 5.342 ±(99.9%) 0.010 ms/op
Iteration   3: 5.051 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.182 ±(99.9%) 2.690 ms/op [Average]
  (min, avg, max) = (5.051, 5.182, 5.342), stdev = 0.147
  CI (99.9%): [2.492, 7.872] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.124 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.317 ±(99.9%) 0.011 ms/op
Iteration   1: 5.500 ±(99.9%) 0.012 ms/op
Iteration   2: 5.427 ±(99.9%) 0.014 ms/op
Iteration   3: 5.245 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.391 ±(99.9%) 2.392 ms/op [Average]
  (min, avg, max) = (5.245, 5.391, 5.500), stdev = 0.131
  CI (99.9%): [2.999, 7.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.152 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 7.640 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.444 ±(99.9%) 0.013 ms/op
Iteration   1: 6.626 ±(99.9%) 0.009 ms/op
Iteration   2: 6.403 ±(99.9%) 0.014 ms/op
Iteration   3: 6.259 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.429 ±(99.9%) 3.368 ms/op [Average]
  (min, avg, max) = (6.259, 6.429, 6.626), stdev = 0.185
  CI (99.9%): [3.061, 9.797] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.774 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.010 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.664 ±(99.9%) 0.026 ms/op
Iteration   1: 5.471 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   10.895 ms/op
                 createUser·p0.999:  23.226 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 5.593 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   10.830 ms/op
                 createUser·p0.999:  31.827 ms/op
                 createUser·p0.9999: 37.356 ms/op
                 createUser·p1.00:   39.322 ms/op

Iteration   3: 5.317 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.114 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   11.525 ms/op
                 createUser·p0.999:  28.062 ms/op
                 createUser·p0.9999: 34.207 ms/op
                 createUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175824
  mean =      5.458 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 78271 
    [ 5.000,  7.500) = 86053 
    [ 7.500, 10.000) = 8738 
    [10.000, 12.500) = 1850 
    [12.500, 15.000) = 504 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 72 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     26.079 ms/op
     p(99.9900) =     35.685 ms/op
     p(99.9990) =     39.123 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.922 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 5.811 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.432 ±(99.9%) 0.023 ms/op
Iteration   1: 5.061 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  25.238 ms/op
                 existUser·p0.9999: 30.791 ms/op
                 existUser·p1.00:   31.818 ms/op

Iteration   2: 5.296 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.075 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.954 ms/op
                 existUser·p0.99:   11.370 ms/op
                 existUser·p0.999:  26.416 ms/op
                 existUser·p0.9999: 31.873 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   3: 5.081 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   10.657 ms/op
                 existUser·p0.999:  28.080 ms/op
                 existUser·p0.9999: 37.356 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186783
  mean =      5.144 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 109600 
    [ 5.000,  7.500) = 67888 
    [ 7.500, 10.000) = 6990 
    [10.000, 12.500) = 1456 
    [12.500, 15.000) = 455 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.487 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     32.931 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.076 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 7.089 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.783 ±(99.9%) 0.025 ms/op
Iteration   1: 5.797 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.873 ms/op
                 getUser·p0.95:   9.257 ms/op
                 getUser·p0.99:   13.484 ms/op
                 getUser·p0.999:  26.155 ms/op
                 getUser·p0.9999: 38.011 ms/op
                 getUser·p1.00:   38.339 ms/op

Iteration   2: 5.939 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   5.562 ms/op
                 getUser·p0.90:   7.832 ms/op
                 getUser·p0.95:   8.978 ms/op
                 getUser·p0.99:   11.544 ms/op
                 getUser·p0.999:  16.024 ms/op
                 getUser·p0.9999: 28.050 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   3: 6.028 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   5.513 ms/op
                 getUser·p0.90:   8.118 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   13.247 ms/op
                 getUser·p0.999:  26.704 ms/op
                 getUser·p0.9999: 32.526 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162084
  mean =      5.920 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 48375 
    [ 5.000,  7.500) = 93216 
    [ 7.500, 10.000) = 14858 
    [10.000, 12.500) = 3897 
    [12.500, 15.000) = 1046 
    [15.000, 17.500) = 284 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.963 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     12.648 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     36.097 ms/op
     p(99.9990) =     38.298 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.898 ±(99.9%) 0.392 ms/op
# Warmup Iteration   2: 8.182 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.676 ±(99.9%) 0.029 ms/op
Iteration   1: 6.688 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.129 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  29.726 ms/op
                 listUser·p0.9999: 41.157 ms/op
                 listUser·p1.00:   41.878 ms/op

Iteration   2: 6.794 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   12.799 ms/op
                 listUser·p0.999:  30.472 ms/op
                 listUser·p0.9999: 35.605 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.708 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.387 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.315 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.730 ms/op
                 listUser·p0.999:  29.650 ms/op
                 listUser·p0.9999: 36.796 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142620
  mean =      6.730 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4119 
    [ 5.000, 10.000) = 131915 
    [10.000, 15.000) = 5984 
    [15.000, 20.000) = 295 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 140 
    [30.000, 35.000) = 89 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.580 ms/op
     p(50.0000) =      6.308 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.863 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     29.864 ms/op
     p(99.9900) =     40.598 ms/op
     p(99.9990) =     41.654 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.242 ± 2.293  ops/ms
ClientPb.existUser                       thrpt       3   6.610 ± 3.147  ops/ms
ClientPb.getUser                         thrpt       3   5.760 ± 5.345  ops/ms
ClientPb.listUser                        thrpt       3   5.140 ± 2.218  ops/ms
ClientPb.createUser                       avgt       3   5.394 ± 3.035   ms/op
ClientPb.existUser                        avgt       3   5.182 ± 2.690   ms/op
ClientPb.getUser                          avgt       3   5.391 ± 2.392   ms/op
ClientPb.listUser                         avgt       3   6.429 ± 3.368   ms/op
ClientPb.createUser                     sample  175824   5.458 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.571           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.922           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.881           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.079           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.685           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  186783   5.144 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.577           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.487           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.657           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.931           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.618           ms/op
ClientPb.getUser                        sample  162084   5.920 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.241           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.648           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.625           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.097           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.339           ms/op
ClientPb.listUser                       sample  142620   6.730 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.580           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.308           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.863           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.598           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.878           ms/op
