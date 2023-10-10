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
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.973 ops/ms
# Warmup Iteration   3: 8.811 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 9.533 ops/ms
Iteration   3: 9.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.655 ±(99.9%) 4.550 ops/ms [Average]
  (min, avg, max) = (9.490, 9.655, 9.942), stdev = 0.249
  CI (99.9%): [5.105, 14.205] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ops/ms
# Warmup Iteration   2: 9.454 ops/ms
# Warmup Iteration   3: 9.818 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.198 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (10.016, 10.198, 10.358), stdev = 0.172
  CI (99.9%): [7.060, 13.337] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.441 ops/ms
# Warmup Iteration   2: 9.057 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 9.642 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.719 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (9.642, 9.719, 9.796), stdev = 0.077
  CI (99.9%): [8.311, 11.128] (assumes normal distribution)


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
# Warmup Iteration   1: 3.045 ops/ms
# Warmup Iteration   2: 7.211 ops/ms
# Warmup Iteration   3: 8.050 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.076 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.212 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (8.076, 8.212, 8.392), stdev = 0.163
  CI (99.9%): [5.247, 11.178] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.501 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.006 ms/op
Iteration   1: 3.395 ±(99.9%) 0.003 ms/op
Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
Iteration   3: 3.281 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.302 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.231, 3.302, 3.395), stdev = 0.084
  CI (99.9%): [1.773, 4.832] (assumes normal distribution)


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
# Warmup Iteration   1: 6.882 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.004 ms/op
Iteration   3: 3.180 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.182 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.159, 3.182, 3.208), stdev = 0.024
  CI (99.9%): [2.738, 3.627] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.002 ms/op
Iteration   1: 3.238 ±(99.9%) 0.003 ms/op
Iteration   2: 3.313 ±(99.9%) 0.004 ms/op
Iteration   3: 3.287 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.279 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.238, 3.279, 3.313), stdev = 0.038
  CI (99.9%): [2.590, 3.969] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.876 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.005 ms/op
Iteration   1: 3.944 ±(99.9%) 0.005 ms/op
Iteration   2: 3.766 ±(99.9%) 0.005 ms/op
Iteration   3: 3.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.863 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (3.766, 3.863, 3.944), stdev = 0.090
  CI (99.9%): [2.226, 5.500] (assumes normal distribution)


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
# Warmup Iteration   1: 7.563 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.011 ms/op
Iteration   1: 3.352 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  18.792 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.308 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  20.205 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   37.421 ms/op

Iteration   3: 3.311 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  19.085 ms/op
                 createUser·p0.9999: 23.484 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288778
  mean =      3.324 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14068 
    [ 2.500,  5.000) = 266398 
    [ 5.000,  7.500) = 6853 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     18.816 ms/op
     p(99.9900) =     35.471 ms/op
     p(99.9990) =     36.941 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 8.660 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
Iteration   1: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  16.845 ms/op
                 existUser·p0.9999: 20.156 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  19.661 ms/op
                 existUser·p0.9999: 25.853 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   6.630 ms/op
                 existUser·p0.999:  15.548 ms/op
                 existUser·p0.9999: 25.473 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297155
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15738 
    [ 2.500,  5.000) = 272795 
    [ 5.000,  7.500) = 7476 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     16.838 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     26.288 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 8.091 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.011 ms/op
Iteration   1: 3.300 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 20.117 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  14.631 ms/op
                 getUser·p0.9999: 27.395 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  15.505 ms/op
                 getUser·p0.9999: 22.191 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293626
  mean =      3.267 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8298 
    [ 2.500,  5.000) = 276137 
    [ 5.000,  7.500) = 7682 
    [ 7.500, 10.000) = 820 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      6.617 ms/op
     p(99.9000) =     16.363 ms/op
     p(99.9900) =     25.503 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 9.152 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.013 ms/op
Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 27.689 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 3.825 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.724 ms/op
                 listUser·p0.9999: 16.839 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  13.510 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250027
  mean =      3.836 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182 
    [ 2.500,  5.000) = 239829 
    [ 5.000,  7.500) = 7447 
    [ 7.500, 10.000) = 1738 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     26.341 ms/op
     p(99.9990) =     27.967 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.655 ± 4.550  ops/ms
ClientPb.existUser                       thrpt       3  10.198 ± 3.139  ops/ms
ClientPb.getUser                         thrpt       3   9.719 ± 1.409  ops/ms
ClientPb.listUser                        thrpt       3   8.212 ± 2.965  ops/ms
ClientPb.createUser                       avgt       3   3.302 ± 1.529   ms/op
ClientPb.existUser                        avgt       3   3.182 ± 0.445   ms/op
ClientPb.getUser                          avgt       3   3.279 ± 0.689   ms/op
ClientPb.listUser                         avgt       3   3.863 ± 1.637   ms/op
ClientPb.createUser                     sample  288778   3.324 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.816           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.471           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.421           ms/op
ClientPb.existUser                      sample  297155   3.229 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.838           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.461           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  293626   3.267 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.006           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.617           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.363           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.503           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  250027   3.836 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.319           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.341           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
