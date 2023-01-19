# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 6.196 ops/ms
# Warmup Iteration   3: 9.334 ops/ms
Iteration   1: 9.528 ops/ms
Iteration   2: 9.994 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.812 ±(99.9%) 4.551 ops/ms [Average]
  (min, avg, max) = (9.528, 9.812, 9.994), stdev = 0.249
  CI (99.9%): [5.261, 14.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ops/ms
# Warmup Iteration   2: 9.656 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.361 ±(99.9%) 5.500 ops/ms [Average]
  (min, avg, max) = (10.137, 10.361, 10.703), stdev = 0.301
  CI (99.9%): [4.861, 15.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.141 ops/ms
Iteration   2: 10.012 ops/ms
Iteration   3: 10.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.173 ±(99.9%) 3.290 ops/ms [Average]
  (min, avg, max) = (10.012, 10.173, 10.368), stdev = 0.180
  CI (99.9%): [6.883, 13.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 7.781 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.768 ops/ms
Iteration   2: 8.730 ops/ms
Iteration   3: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.683 ±(99.9%) 2.113 ops/ms [Average]
  (min, avg, max) = (8.551, 8.683, 8.768), stdev = 0.116
  CI (99.9%): [6.570, 10.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.006 ms/op
Iteration   1: 3.188 ±(99.9%) 0.006 ms/op
Iteration   2: 3.059 ±(99.9%) 0.003 ms/op
Iteration   3: 3.182 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.143 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.059, 3.143, 3.188), stdev = 0.073
  CI (99.9%): [1.814, 4.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.801 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.052 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.009, 3.052, 3.103), stdev = 0.048
  CI (99.9%): [2.183, 3.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.006 ms/op
Iteration   1: 3.193 ±(99.9%) 0.006 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.134 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.145 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.107, 3.145, 3.193), stdev = 0.044
  CI (99.9%): [2.337, 3.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.441 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.004 ms/op
Iteration   1: 3.855 ±(99.9%) 0.006 ms/op
Iteration   2: 3.674 ±(99.9%) 0.008 ms/op
Iteration   3: 3.709 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.746 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.674, 3.746, 3.855), stdev = 0.096
  CI (99.9%): [1.997, 5.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.776 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.009 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.263 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  12.502 ms/op
                 createUser·p0.9999: 22.055 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   2: 3.125 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  19.671 ms/op
                 createUser·p0.9999: 24.437 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  13.190 ms/op
                 createUser·p0.9999: 19.033 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302486
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22395 
    [ 2.500,  5.000) = 274920 
    [ 5.000,  7.500) = 4346 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     15.885 ms/op
     p(99.9900) =     23.880 ms/op
     p(99.9990) =     24.705 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.910 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 22.373 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  10.388 ms/op
                 existUser·p0.9999: 21.555 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  16.325 ms/op
                 existUser·p0.9999: 22.316 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303743
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31566 
    [ 2.500,  5.000) = 265476 
    [ 5.000,  7.500) = 6000 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     15.659 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.196 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.161 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  17.327 ms/op
                 getUser·p0.9999: 19.506 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  8.258 ms/op
                 getUser·p0.9999: 22.340 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  15.728 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298502
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17370 
    [ 2.500,  5.000) = 274307 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     16.064 ms/op
     p(99.9900) =     22.844 ms/op
     p(99.9990) =     24.253 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.464 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.010 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.123 ms/op
                 listUser·p0.9999: 19.755 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 3.630 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.731 ms/op
                 listUser·p0.95:   3.969 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  13.594 ms/op
                 listUser·p0.9999: 15.961 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.616 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  12.297 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262156
  mean =      3.662 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 256027 
    [ 5.000,  7.500) = 4522 
    [ 7.500, 10.000) = 921 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.226 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.812 ± 4.551  ops/ms
ClientPb.existUser                       thrpt       3  10.361 ± 5.500  ops/ms
ClientPb.getUser                         thrpt       3  10.173 ± 3.290  ops/ms
ClientPb.listUser                        thrpt       3   8.683 ± 2.113  ops/ms
ClientPb.createUser                       avgt       3   3.143 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   3.052 ± 0.869   ms/op
ClientPb.getUser                          avgt       3   3.145 ± 0.808   ms/op
ClientPb.listUser                         avgt       3   3.746 ± 1.749   ms/op
ClientPb.createUser                     sample  302486   3.172 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.263           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.885           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.880           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.166           ms/op
ClientPb.existUser                      sample  303743   3.161 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.725           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.659           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  298502   3.212 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.064           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.844           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.133           ms/op
ClientPb.listUser                       sample  262156   3.662 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.431           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.299           ms/op
