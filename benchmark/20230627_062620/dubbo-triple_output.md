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
# Warmup Iteration   1: 2.612 ops/ms
# Warmup Iteration   2: 6.301 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 9.757 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.819 ±(99.9%) 4.786 ops/ms [Average]
  (min, avg, max) = (9.592, 9.819, 10.106), stdev = 0.262
  CI (99.9%): [5.032, 14.605] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ops/ms
# Warmup Iteration   2: 8.782 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.145 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.091 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (10.038, 10.091, 10.145), stdev = 0.054
  CI (99.9%): [9.114, 11.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.477 ops/ms
# Warmup Iteration   2: 9.358 ops/ms
# Warmup Iteration   3: 9.656 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 7.739 ops/ms [Average]
  (min, avg, max) = (9.632, 10.111, 10.439), stdev = 0.424
  CI (99.9%): [2.372, 17.850] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ops/ms
# Warmup Iteration   2: 7.495 ops/ms
# Warmup Iteration   3: 8.627 ops/ms
Iteration   1: 8.462 ops/ms
Iteration   2: 8.815 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.626 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (8.462, 8.626, 8.815), stdev = 0.177
  CI (99.9%): [5.389, 11.864] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.102 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.003 ms/op
Iteration   1: 3.326 ±(99.9%) 0.005 ms/op
Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
Iteration   3: 3.118 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.204 ±(99.9%) 1.979 ms/op [Average]
  (min, avg, max) = (3.118, 3.204, 3.326), stdev = 0.108
  CI (99.9%): [1.224, 5.183] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.028 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.006 ms/op
Iteration   1: 3.182 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.085 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (3.027, 3.085, 3.182), stdev = 0.085
  CI (99.9%): [1.532, 4.638] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.067 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.006 ms/op
Iteration   1: 3.301 ±(99.9%) 0.004 ms/op
Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
Iteration   3: 3.206 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (3.165, 3.224, 3.301), stdev = 0.070
  CI (99.9%): [1.951, 4.497] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.992 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.008 ms/op
Iteration   1: 3.697 ±(99.9%) 0.010 ms/op
Iteration   2: 3.700 ±(99.9%) 0.010 ms/op
Iteration   3: 3.762 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.697, 3.720, 3.762), stdev = 0.037
  CI (99.9%): [3.046, 4.394] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.943 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  10.173 ms/op
                 createUser·p0.9999: 22.060 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  19.074 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  16.624 ms/op
                 createUser·p0.9999: 26.351 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294849
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24586 
    [ 2.500,  5.000) = 264744 
    [ 5.000,  7.500) = 4568 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.709 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
Iteration   1: 3.203 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  15.583 ms/op
                 existUser·p0.9999: 20.153 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.143 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.438 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 23.331 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  8.973 ms/op
                 existUser·p0.9999: 24.147 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302507
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24633 
    [ 2.500,  5.000) = 271454 
    [ 5.000,  7.500) = 5357 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     13.761 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 7.767 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  14.771 ms/op
                 getUser·p0.9999: 19.994 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  8.595 ms/op
                 getUser·p0.9999: 23.461 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 27.291 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298991
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12756 
    [ 2.500,  5.000) = 279435 
    [ 5.000,  7.500) = 5950 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.809 ms/op
     p(99.9000) =     14.468 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 8.819 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.013 ms/op
Iteration   1: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 20.265 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.717 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.764 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 17.315 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.657 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.047 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 20.816 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258655
  mean =      3.708 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 252080 
    [ 5.000,  7.500) = 4783 
    [ 7.500, 10.000) = 1008 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     20.231 ms/op
     p(99.9990) =     20.993 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.819 ± 4.786  ops/ms
ClientPb.existUser                       thrpt       3  10.091 ± 0.977  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 7.739  ops/ms
ClientPb.listUser                        thrpt       3   8.626 ± 3.238  ops/ms
ClientPb.createUser                       avgt       3   3.204 ± 1.979   ms/op
ClientPb.existUser                        avgt       3   3.085 ± 1.553   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 1.273   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 0.674   ms/op
ClientPb.createUser                     sample  294849   3.254 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.099           ms/op
ClientPb.existUser                      sample  302507   3.171 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.761           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.560           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  298991   3.208 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.973           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.809           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.468           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.723           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  258655   3.708 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.636           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.550           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.231           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
