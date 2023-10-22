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
# Warmup Iteration   1: 2.473 ops/ms
# Warmup Iteration   2: 6.286 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.879 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.878 ±(99.9%) 0.146 ops/ms [Average]
  (min, avg, max) = (9.869, 9.878, 9.885), stdev = 0.008
  CI (99.9%): [9.731, 10.024] (assumes normal distribution)


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
# Warmup Iteration   1: 3.506 ops/ms
# Warmup Iteration   2: 9.157 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.198 ops/ms
Iteration   2: 10.050 ops/ms
Iteration   3: 9.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.038 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (9.865, 10.038, 10.198), stdev = 0.167
  CI (99.9%): [6.991, 13.084] (assumes normal distribution)


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
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 9.453 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 9.841 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.817 ±(99.9%) 1.363 ops/ms [Average]
  (min, avg, max) = (9.733, 9.817, 9.877), stdev = 0.075
  CI (99.9%): [8.454, 11.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 7.816 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.298 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (8.269, 8.298, 8.347), stdev = 0.043
  CI (99.9%): [7.518, 9.077] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.663 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.003 ms/op
Iteration   1: 3.289 ±(99.9%) 0.002 ms/op
Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.257 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.214, 3.257, 3.289), stdev = 0.039
  CI (99.9%): [2.553, 3.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.645 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.004 ms/op
Iteration   1: 3.213 ±(99.9%) 0.005 ms/op
Iteration   2: 3.126 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.170 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.126, 3.170, 3.213), stdev = 0.043
  CI (99.9%): [2.376, 3.963] (assumes normal distribution)


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
# Warmup Iteration   1: 7.704 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.003 ms/op
Iteration   1: 3.260 ±(99.9%) 0.002 ms/op
Iteration   2: 3.282 ±(99.9%) 0.003 ms/op
Iteration   3: 3.260 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.267 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.260, 3.267, 3.282), stdev = 0.013
  CI (99.9%): [3.033, 3.502] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.479 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.003 ms/op
Iteration   1: 3.884 ±(99.9%) 0.005 ms/op
Iteration   2: 3.863 ±(99.9%) 0.005 ms/op
Iteration   3: 3.874 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.874 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.863, 3.874, 3.884), stdev = 0.011
  CI (99.9%): [3.680, 4.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.100 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.355 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 31.881 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   2: 3.289 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  19.621 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  17.834 ms/op
                 createUser·p0.9999: 30.029 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287870
  mean =      3.333 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14810 
    [ 2.500,  5.000) = 267136 
    [ 5.000,  7.500) = 4453 
    [ 7.500, 10.000) = 684 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     18.129 ms/op
     p(99.9900) =     31.104 ms/op
     p(99.9990) =     32.379 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.466 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
Iteration   1: 3.221 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.929 ms/op
                 existUser·p0.99:   5.912 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 22.317 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  11.286 ms/op
                 existUser·p0.9999: 19.882 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 3.199 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  15.401 ms/op
                 existUser·p0.9999: 40.436 ms/op
                 existUser·p1.00:   42.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300663
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 295014 
    [ 5.000, 10.000) = 5197 
    [10.000, 15.000) = 188 
    [15.000, 20.000) = 173 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     36.691 ms/op
     p(99.9990) =     41.681 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


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
# Warmup Iteration   1: 7.972 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.011 ms/op
Iteration   1: 3.353 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  17.930 ms/op
                 getUser·p0.9999: 21.065 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  8.478 ms/op
                 getUser·p0.9999: 22.960 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.391 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  13.217 ms/op
                 getUser·p0.9999: 21.106 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295746
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8404 
    [ 2.500,  5.000) = 280748 
    [ 5.000,  7.500) = 5576 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     13.505 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.110 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 9.520 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
Iteration   1: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.377 ms/op
                 listUser·p0.9999: 22.536 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.901 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 17.243 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.886 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.470 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 19.207 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246006
  mean =      3.900 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 239777 
    [ 5.000,  7.500) = 4816 
    [ 7.500, 10.000) = 653 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     21.063 ms/op
     p(99.9990) =     24.178 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.878 ± 0.146  ops/ms
ClientPb.existUser                       thrpt       3  10.038 ± 3.047  ops/ms
ClientPb.getUser                         thrpt       3   9.817 ± 1.363  ops/ms
ClientPb.listUser                        thrpt       3   8.298 ± 0.779  ops/ms
ClientPb.createUser                       avgt       3   3.257 ± 0.705   ms/op
ClientPb.existUser                        avgt       3   3.170 ± 0.793   ms/op
ClientPb.getUser                          avgt       3   3.267 ± 0.234   ms/op
ClientPb.listUser                         avgt       3   3.874 ± 0.194   ms/op
ClientPb.createUser                     sample  287870   3.333 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.129           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.104           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.637           ms/op
ClientPb.existUser                      sample  300663   3.192 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.902           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.691           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.467           ms/op
ClientPb.getUser                        sample  295746   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.505           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.922           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.429           ms/op
ClientPb.listUser                       sample  246006   3.900 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.781           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.063           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
