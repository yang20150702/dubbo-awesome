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
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 5.438 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 9.016 ops/ms
Iteration   3: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.891 ±(99.9%) 4.778 ops/ms [Average]
  (min, avg, max) = (8.590, 8.891, 9.068), stdev = 0.262
  CI (99.9%): [4.114, 13.669] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 8.474 ops/ms
# Warmup Iteration   3: 9.308 ops/ms
Iteration   1: 9.411 ops/ms
Iteration   2: 9.531 ops/ms
Iteration   3: 9.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.472 ±(99.9%) 1.096 ops/ms [Average]
  (min, avg, max) = (9.411, 9.472, 9.531), stdev = 0.060
  CI (99.9%): [8.376, 10.568] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.659 ops/ms
# Warmup Iteration   2: 8.230 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 9.178 ops/ms
Iteration   2: 8.977 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.124 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (8.977, 9.124, 9.218), stdev = 0.129
  CI (99.9%): [6.767, 11.481] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 6.989 ops/ms
# Warmup Iteration   3: 7.481 ops/ms
Iteration   1: 7.480 ops/ms
Iteration   2: 7.647 ops/ms
Iteration   3: 7.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.629 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (7.480, 7.629, 7.761), stdev = 0.141
  CI (99.9%): [5.049, 10.209] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.117 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.003 ms/op
Iteration   1: 3.541 ±(99.9%) 0.005 ms/op
Iteration   2: 3.585 ±(99.9%) 0.004 ms/op
Iteration   3: 3.576 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.568 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.541, 3.568, 3.585), stdev = 0.023
  CI (99.9%): [3.142, 3.993] (assumes normal distribution)


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
# Warmup Iteration   1: 11.520 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.005 ms/op
Iteration   1: 3.501 ±(99.9%) 0.003 ms/op
Iteration   2: 3.450 ±(99.9%) 0.004 ms/op
Iteration   3: 3.473 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.475 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.450, 3.475, 3.501), stdev = 0.026
  CI (99.9%): [3.006, 3.944] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.503 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.003 ms/op
Iteration   1: 3.634 ±(99.9%) 0.004 ms/op
Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
Iteration   3: 3.561 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.598 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.561, 3.598, 3.634), stdev = 0.037
  CI (99.9%): [2.927, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 13.649 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.004 ms/op
Iteration   1: 4.266 ±(99.9%) 0.004 ms/op
Iteration   2: 4.221 ±(99.9%) 0.006 ms/op
Iteration   3: 4.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.233 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (4.212, 4.233, 4.266), stdev = 0.029
  CI (99.9%): [3.705, 4.761] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.672 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.016 ms/op
Iteration   1: 3.559 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.637 ms/op
                 createUser·p0.999:  21.733 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.565 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  24.653 ms/op
                 createUser·p0.9999: 31.166 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   3: 3.568 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.197 ms/op
                 createUser·p0.999:  22.523 ms/op
                 createUser·p0.9999: 28.906 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269365
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3881 
    [ 2.500,  5.000) = 259219 
    [ 5.000,  7.500) = 4643 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     29.760 ms/op
     p(99.9990) =     31.618 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 9.585 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.008 ms/op
Iteration   1: 3.463 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 25.322 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  24.324 ms/op
                 existUser·p0.9999: 26.921 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.426 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  20.709 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278637
  mean =      3.446 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5934 
    [ 2.500,  5.000) = 265884 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 119 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     20.942 ms/op
     p(99.9900) =     26.940 ms/op
     p(99.9990) =     28.417 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 11.052 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.014 ms/op
Iteration   1: 3.557 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  20.414 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   2: 3.596 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  11.665 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.557 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  24.674 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268830
  mean =      3.570 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1825 
    [ 2.500,  5.000) = 260620 
    [ 5.000,  7.500) = 4817 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     27.303 ms/op
     p(99.9990) =     29.825 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 12.503 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.014 ms/op
Iteration   1: 4.203 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.702 ms/op
                 listUser·p0.999:  20.168 ms/op
                 listUser·p0.9999: 23.114 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.167 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 17.880 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 4.177 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 18.515 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229310
  mean =      4.182 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 221191 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 1235 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 263 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     22.062 ms/op
     p(99.9990) =     23.609 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.891 ± 4.778  ops/ms
ClientPb.existUser                       thrpt       3   9.472 ± 1.096  ops/ms
ClientPb.getUser                         thrpt       3   9.124 ± 2.357  ops/ms
ClientPb.listUser                        thrpt       3   7.629 ± 2.580  ops/ms
ClientPb.createUser                       avgt       3   3.568 ± 0.426   ms/op
ClientPb.existUser                        avgt       3   3.475 ± 0.469   ms/op
ClientPb.getUser                          avgt       3   3.598 ± 0.671   ms/op
ClientPb.listUser                         avgt       3   4.233 ± 0.528   ms/op
ClientPb.createUser                     sample  269365   3.564 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.178           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.413           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.760           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.161           ms/op
ClientPb.existUser                      sample  278637   3.446 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.526           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.940           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  268830   3.570 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.983           ms/op
ClientPb.listUser                       sample  229310   4.182 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.062           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
