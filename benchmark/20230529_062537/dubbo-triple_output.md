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
# Warmup Iteration   1: 2.813 ops/ms
# Warmup Iteration   2: 6.970 ops/ms
# Warmup Iteration   3: 9.514 ops/ms
Iteration   1: 9.856 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.793 ±(99.9%) 5.542 ops/ms [Average]
  (min, avg, max) = (9.463, 9.793, 10.061), stdev = 0.304
  CI (99.9%): [4.251, 15.335] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ops/ms
# Warmup Iteration   2: 9.787 ops/ms
# Warmup Iteration   3: 10.096 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.443 ±(99.9%) 8.206 ops/ms [Average]
  (min, avg, max) = (9.924, 10.443, 10.723), stdev = 0.450
  CI (99.9%): [2.237, 18.649] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 9.084 ops/ms
# Warmup Iteration   3: 9.698 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 10.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.214 ±(99.9%) 3.880 ops/ms [Average]
  (min, avg, max) = (9.979, 10.214, 10.394), stdev = 0.213
  CI (99.9%): [6.334, 14.094] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ops/ms
# Warmup Iteration   2: 7.852 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.571 ops/ms
Iteration   3: 8.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.618 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (8.515, 8.618, 8.767), stdev = 0.132
  CI (99.9%): [6.206, 11.029] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.828 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.005 ms/op
Iteration   1: 3.143 ±(99.9%) 0.004 ms/op
Iteration   2: 3.128 ±(99.9%) 0.004 ms/op
Iteration   3: 3.140 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (3.128, 3.137, 3.143), stdev = 0.008
  CI (99.9%): [2.993, 3.282] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.565 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.004 ms/op
Iteration   1: 3.140 ±(99.9%) 0.006 ms/op
Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.053 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (3.008, 3.053, 3.140), stdev = 0.075
  CI (99.9%): [1.685, 4.422] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.007 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.006 ms/op
Iteration   1: 3.127 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.208 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.148 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.107, 3.148, 3.208), stdev = 0.054
  CI (99.9%): [2.169, 4.126] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.759 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.004 ms/op
Iteration   1: 3.800 ±(99.9%) 0.007 ms/op
Iteration   2: 3.733 ±(99.9%) 0.006 ms/op
Iteration   3: 3.804 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.779 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.733, 3.779, 3.804), stdev = 0.040
  CI (99.9%): [3.050, 4.508] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.638 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 22.639 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  13.518 ms/op
                 createUser·p0.9999: 20.215 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306353
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7964 
    [ 2.500,  5.000) = 294661 
    [ 5.000,  7.500) = 2930 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.841 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.671 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 20.291 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.281 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  18.874 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  10.150 ms/op
                 existUser·p0.9999: 21.065 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302623
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33191 
    [ 2.500,  5.000) = 263429 
    [ 5.000,  7.500) = 5170 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     13.904 ms/op
     p(99.9900) =     25.018 ms/op
     p(99.9990) =     27.817 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 9.015 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  17.163 ms/op
                 getUser·p0.9999: 20.240 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.253 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.372 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298094
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9826 
    [ 2.500,  5.000) = 281327 
    [ 5.000,  7.500) = 5969 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     13.745 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.572 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 21.801 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.810 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  12.943 ms/op
                 listUser·p0.9999: 15.034 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.634 ms/op
                 listUser·p0.999:  16.279 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254299
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 122 
    [ 2.500,  5.000) = 245653 
    [ 5.000,  7.500) = 6121 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     22.254 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.793 ± 5.542  ops/ms
ClientPb.existUser                       thrpt       3  10.443 ± 8.206  ops/ms
ClientPb.getUser                         thrpt       3  10.214 ± 3.880  ops/ms
ClientPb.listUser                        thrpt       3   8.618 ± 2.411  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 0.145   ms/op
ClientPb.existUser                        avgt       3   3.053 ± 1.368   ms/op
ClientPb.getUser                          avgt       3   3.148 ± 0.978   ms/op
ClientPb.listUser                         avgt       3   3.779 ± 0.729   ms/op
ClientPb.createUser                     sample  306353   3.132 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.811           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  302623   3.171 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.281           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.904           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  298094   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.071           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.199           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  254299   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.762           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
