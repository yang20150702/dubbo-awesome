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
# Warmup Iteration   1: 2.618 ops/ms
# Warmup Iteration   2: 5.886 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.721 ±(99.9%) 0.458 ops/ms [Average]
  (min, avg, max) = (9.694, 9.721, 9.744), stdev = 0.025
  CI (99.9%): [9.262, 10.179] (assumes normal distribution)


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
# Warmup Iteration   1: 3.245 ops/ms
# Warmup Iteration   2: 8.945 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.121 ops/ms
Iteration   2: 10.169 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.181 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (10.121, 10.181, 10.252), stdev = 0.066
  CI (99.9%): [8.969, 11.393] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 9.471 ops/ms
Iteration   1: 9.703 ops/ms
Iteration   2: 9.789 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.783 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (9.703, 9.783, 9.856), stdev = 0.077
  CI (99.9%): [8.385, 11.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.064 ops/ms
# Warmup Iteration   2: 7.601 ops/ms
# Warmup Iteration   3: 8.224 ops/ms
Iteration   1: 8.235 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.290 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (8.235, 8.290, 8.326), stdev = 0.048
  CI (99.9%): [7.407, 9.173] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.004 ms/op
Iteration   1: 3.380 ±(99.9%) 0.002 ms/op
Iteration   2: 3.270 ±(99.9%) 0.005 ms/op
Iteration   3: 3.225 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.292 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.225, 3.292, 3.380), stdev = 0.080
  CI (99.9%): [1.832, 4.752] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.866 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.001 ms/op
Iteration   1: 3.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
Iteration   3: 3.148 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.143 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.136, 3.143, 3.148), stdev = 0.006
  CI (99.9%): [3.035, 3.251] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.398 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.002 ms/op
Iteration   1: 3.258 ±(99.9%) 0.002 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.244 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.200, 3.234, 3.258), stdev = 0.030
  CI (99.9%): [2.681, 3.786] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.392 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.005 ms/op
Iteration   1: 3.772 ±(99.9%) 0.005 ms/op
Iteration   2: 3.857 ±(99.9%) 0.004 ms/op
Iteration   3: 3.738 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.789 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (3.738, 3.789, 3.857), stdev = 0.061
  CI (99.9%): [2.676, 4.902] (assumes normal distribution)


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
# Warmup Iteration   1: 8.281 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.253 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.203 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  20.090 ms/op
                 createUser·p0.9999: 24.020 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  16.391 ms/op
                 createUser·p0.9999: 19.088 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296483
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10928 
    [ 2.500,  5.000) = 281099 
    [ 5.000,  7.500) = 3584 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     22.064 ms/op
     p(99.9990) =     24.680 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.182 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.772 ms/op
                 existUser·p0.9999: 19.427 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  10.705 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.167 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  14.041 ms/op
                 existUser·p0.9999: 24.409 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300986
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14056 
    [ 2.500,  5.000) = 280529 
    [ 5.000,  7.500) = 5448 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     13.240 ms/op
     p(99.9900) =     22.508 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 7.841 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  18.850 ms/op
                 getUser·p0.9999: 23.279 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  16.512 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  15.774 ms/op
                 getUser·p0.9999: 21.450 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290923
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10751 
    [ 2.500,  5.000) = 274313 
    [ 5.000,  7.500) = 4927 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     22.541 ms/op
     p(99.9990) =     23.477 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 9.691 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.010 ms/op
Iteration   1: 3.852 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 19.285 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.844 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.350 ms/op
                 listUser·p0.9999: 18.165 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.919 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 20.318 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247887
  mean =      3.872 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 240846 
    [ 5.000,  7.500) = 5249 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     19.635 ms/op
     p(99.9990) =     21.121 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.721 ± 0.458  ops/ms
ClientPb.existUser                       thrpt       3  10.181 ± 1.212  ops/ms
ClientPb.getUser                         thrpt       3   9.783 ± 1.397  ops/ms
ClientPb.listUser                        thrpt       3   8.290 ± 0.883  ops/ms
ClientPb.createUser                       avgt       3   3.292 ± 1.460   ms/op
ClientPb.existUser                        avgt       3   3.143 ± 0.108   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 0.553   ms/op
ClientPb.listUser                         avgt       3   3.789 ± 1.113   ms/op
ClientPb.createUser                     sample  296483   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.742           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.064           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.904           ms/op
ClientPb.existUser                      sample  300986   3.185 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.240           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  290923   3.297 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.888           ms/op
ClientPb.listUser                       sample  247887   3.872 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.635           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
