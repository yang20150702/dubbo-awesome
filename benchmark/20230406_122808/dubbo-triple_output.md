# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.496 ops/ms
# Warmup Iteration   2: 5.804 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 9.832 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.961 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (9.832, 9.961, 10.060), stdev = 0.117
  CI (99.9%): [7.826, 12.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 9.538 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.257 ops/ms
Iteration   2: 10.864 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.445 ±(99.9%) 6.635 ops/ms [Average]
  (min, avg, max) = (10.213, 10.445, 10.864), stdev = 0.364
  CI (99.9%): [3.810, 17.079] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 8.916 ops/ms
# Warmup Iteration   3: 9.688 ops/ms
Iteration   1: 10.374 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.280 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (10.200, 10.280, 10.374), stdev = 0.088
  CI (99.9%): [8.675, 11.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 7.911 ops/ms
# Warmup Iteration   3: 8.265 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.660 ops/ms
Iteration   3: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.676 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (8.613, 8.676, 8.755), stdev = 0.072
  CI (99.9%): [7.354, 9.999] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.973 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.003 ms/op
Iteration   1: 3.111 ±(99.9%) 0.005 ms/op
Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
Iteration   3: 3.110 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.110, 3.137, 3.191), stdev = 0.047
  CI (99.9%): [2.286, 3.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.005 ms/op
Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
Iteration   3: 3.066 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.060 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.051, 3.060, 3.066), stdev = 0.008
  CI (99.9%): [2.908, 3.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.686 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.127 ±(99.9%) 0.002 ms/op
Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
Iteration   3: 3.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.154 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.113, 3.154, 3.222), stdev = 0.060
  CI (99.9%): [2.066, 4.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.492 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.006 ms/op
Iteration   1: 3.665 ±(99.9%) 0.011 ms/op
Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
Iteration   3: 3.669 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.656 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.632, 3.656, 3.669), stdev = 0.020
  CI (99.9%): [3.286, 4.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.207 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.772 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 19.841 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  12.675 ms/op
                 createUser·p0.9999: 22.674 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  15.690 ms/op
                 createUser·p0.9999: 21.087 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292512
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19449 
    [ 2.500,  5.000) = 264815 
    [ 5.000,  7.500) = 7299 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.782 ms/op
     p(99.9000) =     16.441 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.204 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.226 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  18.084 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  12.647 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 21.290 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305983
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19083 
    [ 2.500,  5.000) = 280469 
    [ 5.000,  7.500) = 5619 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     13.977 ms/op
     p(99.9900) =     21.607 ms/op
     p(99.9990) =     23.259 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
Iteration   1: 3.169 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   4.046 ms/op
                 getUser·p0.99:   6.032 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 26.470 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.417 ms/op
                 getUser·p0.9999: 20.748 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.283 ms/op
                 getUser·p0.9999: 28.639 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300094
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26020 
    [ 2.500,  5.000) = 266586 
    [ 5.000,  7.500) = 6647 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     27.983 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.510 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.734 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.493 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 20.658 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 3.667 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 26.182 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258918
  mean =      3.705 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 251856 
    [ 5.000,  7.500) = 5254 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     23.203 ms/op
     p(99.9990) =     26.760 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.961 ± 2.134  ops/ms
ClientPb.existUser                       thrpt       3  10.445 ± 6.635  ops/ms
ClientPb.getUser                         thrpt       3  10.280 ± 1.605  ops/ms
ClientPb.listUser                        thrpt       3   8.676 ± 1.323  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 0.852   ms/op
ClientPb.existUser                        avgt       3   3.060 ± 0.152   ms/op
ClientPb.getUser                          avgt       3   3.154 ± 1.088   ms/op
ClientPb.listUser                         avgt       3   3.656 ± 0.369   ms/op
ClientPb.createUser                     sample  292512   3.283 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.120           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.782           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.441           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.281           ms/op
ClientPb.existUser                      sample  305983   3.136 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.981           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.607           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.527           ms/op
ClientPb.getUser                        sample  300094   3.199 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.384           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  258918   3.705 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.203           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
