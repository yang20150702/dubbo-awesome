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
# Warmup Iteration   1: 1.704 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 9.166 ops/ms
Iteration   2: 9.186 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.323 ±(99.9%) 4.658 ops/ms [Average]
  (min, avg, max) = (9.166, 9.323, 9.618), stdev = 0.255
  CI (99.9%): [4.666, 13.981] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.634 ops/ms
# Warmup Iteration   2: 8.073 ops/ms
# Warmup Iteration   3: 9.080 ops/ms
Iteration   1: 9.539 ops/ms
Iteration   2: 9.376 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.524 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (9.376, 9.524, 9.658), stdev = 0.141
  CI (99.9%): [6.945, 12.104] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.822 ops/ms
# Warmup Iteration   2: 8.156 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 9.071 ops/ms
Iteration   2: 9.610 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.394 ±(99.9%) 5.197 ops/ms [Average]
  (min, avg, max) = (9.071, 9.394, 9.610), stdev = 0.285
  CI (99.9%): [4.197, 14.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.702 ops/ms
# Warmup Iteration   2: 7.319 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 7.930 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.916 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (7.830, 7.916, 7.989), stdev = 0.080
  CI (99.9%): [6.452, 9.381] (assumes normal distribution)


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
# Warmup Iteration   1: 8.921 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.012 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
Iteration   2: 3.455 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.384 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (3.325, 3.384, 3.455), stdev = 0.066
  CI (99.9%): [2.177, 4.591] (assumes normal distribution)


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
# Warmup Iteration   1: 9.136 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.008 ms/op
Iteration   1: 3.401 ±(99.9%) 0.007 ms/op
Iteration   2: 3.403 ±(99.9%) 0.005 ms/op
Iteration   3: 3.423 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.409 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.401, 3.409, 3.423), stdev = 0.012
  CI (99.9%): [3.192, 3.626] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.891 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.005 ms/op
Iteration   1: 3.458 ±(99.9%) 0.007 ms/op
Iteration   2: 3.515 ±(99.9%) 0.008 ms/op
Iteration   3: 3.426 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.426, 3.467, 3.515), stdev = 0.045
  CI (99.9%): [2.641, 4.292] (assumes normal distribution)


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
# Warmup Iteration   1: 10.914 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.007 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
Iteration   2: 3.964 ±(99.9%) 0.013 ms/op
Iteration   3: 4.017 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.006 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.964, 4.006, 4.036), stdev = 0.037
  CI (99.9%): [3.325, 4.686] (assumes normal distribution)


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
# Warmup Iteration   1: 9.570 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.012 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.878 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 26.995 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  23.167 ms/op
                 createUser·p0.9999: 26.176 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 26.633 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279835
  mean =      3.429 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9440 
    [ 2.500,  5.000) = 264689 
    [ 5.000,  7.500) = 4596 
    [ 7.500, 10.000) = 623 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 9.669 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
Iteration   1: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  14.953 ms/op
                 existUser·p0.9999: 22.501 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  14.315 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  19.977 ms/op
                 existUser·p0.9999: 30.694 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287562
  mean =      3.336 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17374 
    [ 2.500,  5.000) = 264121 
    [ 5.000,  7.500) = 4858 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     19.788 ms/op
     p(99.9900) =     29.106 ms/op
     p(99.9990) =     31.146 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.013 ms/op
Iteration   1: 3.479 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  15.909 ms/op
                 getUser·p0.9999: 23.547 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.344 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  21.251 ms/op
                 getUser·p0.9999: 25.390 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 3.492 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  20.629 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279192
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1190 
    [ 2.500,  5.000) = 270074 
    [ 5.000,  7.500) = 6216 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     19.223 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     26.810 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 12.226 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.014 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  21.064 ms/op
                 listUser·p0.9999: 24.542 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.615 ms/op
                 listUser·p0.9999: 17.532 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 3.920 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  17.644 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241643
  mean =      3.969 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 234835 
    [ 5.000,  7.500) = 4782 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     16.434 ms/op
     p(99.9900) =     23.484 ms/op
     p(99.9990) =     24.797 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.323 ± 4.658  ops/ms
ClientPb.existUser                       thrpt       3   9.524 ± 2.580  ops/ms
ClientPb.getUser                         thrpt       3   9.394 ± 5.197  ops/ms
ClientPb.listUser                        thrpt       3   7.916 ± 1.464  ops/ms
ClientPb.createUser                       avgt       3   3.384 ± 1.207   ms/op
ClientPb.existUser                        avgt       3   3.409 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 0.826   ms/op
ClientPb.listUser                         avgt       3   4.006 ± 0.681   ms/op
ClientPb.createUser                     sample  279835   3.429 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.608           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  287562   3.336 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.292           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.788           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.106           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  279192   3.437 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.255           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.223           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.262           ms/op
ClientPb.listUser                       sample  241643   3.969 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.964           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
