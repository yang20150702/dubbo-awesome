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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 5.597 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.836 ops/ms
Iteration   3: 9.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.728 ±(99.9%) 1.820 ops/ms [Average]
  (min, avg, max) = (9.639, 9.728, 9.836), stdev = 0.100
  CI (99.9%): [7.908, 11.548] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ops/ms
# Warmup Iteration   2: 9.461 ops/ms
# Warmup Iteration   3: 9.680 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.333 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.250 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (10.208, 10.250, 10.333), stdev = 0.072
  CI (99.9%): [8.934, 11.566] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 10.139 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 10.106 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.006 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (9.938, 10.006, 10.106), stdev = 0.088
  CI (99.9%): [8.398, 11.615] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.544 ±(99.9%) 2.163 ops/ms [Average]
  (min, avg, max) = (8.433, 8.544, 8.669), stdev = 0.119
  CI (99.9%): [6.381, 10.708] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
Iteration   2: 3.138 ±(99.9%) 0.005 ms/op
Iteration   3: 3.209 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.178 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.138, 3.178, 3.209), stdev = 0.036
  CI (99.9%): [2.522, 3.834] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
Iteration   3: 3.177 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.178 ±(99.9%) 0.900 ms/op [Average]
  (min, avg, max) = (3.128, 3.178, 3.227), stdev = 0.049
  CI (99.9%): [2.277, 4.078] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.002 ms/op
Iteration   1: 3.237 ±(99.9%) 0.004 ms/op
Iteration   2: 3.329 ±(99.9%) 0.003 ms/op
Iteration   3: 3.326 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.297 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.237, 3.297, 3.329), stdev = 0.052
  CI (99.9%): [2.345, 4.249] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.007 ms/op
Iteration   1: 3.745 ±(99.9%) 0.012 ms/op
Iteration   2: 3.820 ±(99.9%) 0.007 ms/op
Iteration   3: 3.735 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.767 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.735, 3.767, 3.820), stdev = 0.046
  CI (99.9%): [2.924, 4.609] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.902 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  9.784 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301183
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21695 
    [ 2.500,  5.000) = 273921 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     24.827 ms/op
     p(99.9990) =     26.803 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.412 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.060 ms/op
                 existUser·p0.9999: 19.708 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 22.570 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.212 ms/op
                 existUser·p0.999:  14.885 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313530
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26320 
    [ 2.500,  5.000) = 282765 
    [ 5.000,  7.500) = 3665 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.420 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     13.459 ms/op
     p(99.9900) =     21.648 ms/op
     p(99.9990) =     23.634 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
Iteration   1: 3.283 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 26.585 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 25.071 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  15.004 ms/op
                 getUser·p0.9999: 20.820 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292788
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13838 
    [ 2.500,  5.000) = 272565 
    [ 5.000,  7.500) = 5286 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     15.733 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     33.751 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.037 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.713 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.525 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.950 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.728 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257558
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 248681 
    [ 5.000,  7.500) = 6934 
    [ 7.500, 10.000) = 1148 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.804 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     21.233 ms/op
     p(99.9990) =     22.782 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.728 ± 1.820  ops/ms
ClientPb.existUser                       thrpt       3  10.250 ± 1.316  ops/ms
ClientPb.getUser                         thrpt       3  10.006 ± 1.609  ops/ms
ClientPb.listUser                        thrpt       3   8.544 ± 2.163  ops/ms
ClientPb.createUser                       avgt       3   3.178 ± 0.656   ms/op
ClientPb.existUser                        avgt       3   3.178 ± 0.900   ms/op
ClientPb.getUser                          avgt       3   3.297 ± 0.952   ms/op
ClientPb.listUser                         avgt       3   3.767 ± 0.843   ms/op
ClientPb.createUser                     sample  301183   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.153           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.827           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.034           ms/op
ClientPb.existUser                      sample  313530   3.062 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.126           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.459           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.035           ms/op
ClientPb.getUser                        sample  292788   3.277 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.199           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  257558   3.727 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.200           ms/op
