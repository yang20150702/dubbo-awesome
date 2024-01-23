# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ops/ms
# Warmup Iteration   2: 12.078 ops/ms
# Warmup Iteration   3: 12.267 ops/ms
Iteration   1: 12.571 ops/ms
Iteration   2: 12.491 ops/ms
Iteration   3: 12.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.570 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (12.491, 12.570, 12.647), stdev = 0.078
  CI (99.9%): [11.145, 13.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ops/ms
# Warmup Iteration   2: 13.149 ops/ms
# Warmup Iteration   3: 13.329 ops/ms
Iteration   1: 13.318 ops/ms
Iteration   2: 13.338 ops/ms
Iteration   3: 13.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.288 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (13.209, 13.288, 13.338), stdev = 0.070
  CI (99.9%): [12.020, 14.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.002 ops/ms
# Warmup Iteration   2: 12.715 ops/ms
# Warmup Iteration   3: 12.835 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 13.007 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.964 ±(99.9%) 0.682 ops/ms [Average]
  (min, avg, max) = (12.942, 12.964, 13.007), stdev = 0.037
  CI (99.9%): [12.282, 13.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.644 ops/ms
# Warmup Iteration   2: 10.744 ops/ms
# Warmup Iteration   3: 10.832 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.732 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.702 ±(99.9%) 0.633 ops/ms [Average]
  (min, avg, max) = (10.664, 10.702, 10.732), stdev = 0.035
  CI (99.9%): [10.069, 11.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.003 ms/op
Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.543 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.527, 2.543, 2.565), stdev = 0.020
  CI (99.9%): [2.177, 2.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.003 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.411, 2.422, 2.438), stdev = 0.014
  CI (99.9%): [2.163, 2.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.434 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (2.432, 2.434, 2.439), stdev = 0.004
  CI (99.9%): [2.368, 2.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.763 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.981 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.973, 2.981, 2.991), stdev = 0.009
  CI (99.9%): [2.812, 3.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.926 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.418 ms/op
                 createUser·p0.9999: 11.375 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.581 ms/op
                 createUser·p0.9999: 10.568 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383050
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 184790 
    [ 2.500,  3.750) = 193853 
    [ 3.750,  5.000) = 2868 
    [ 5.000,  6.250) = 1003 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.516 ms/op
     p(99.9900) =     13.245 ms/op
     p(99.9990) =     13.957 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.714 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.712 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.713 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 13.133 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.127 ms/op
                 existUser·p0.9999: 11.646 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396923
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 199857 
    [ 2.500,  3.750) = 193851 
    [ 3.750,  5.000) = 2510 
    [ 5.000,  6.250) = 260 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.309 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.653 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  11.291 ms/op
                 getUser·p0.9999: 13.822 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  6.635 ms/op
                 getUser·p0.9999: 13.666 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  8.217 ms/op
                 getUser·p0.9999: 11.811 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384546
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 191636 
    [ 2.500,  3.750) = 187527 
    [ 3.750,  5.000) = 4084 
    [ 5.000,  6.250) = 755 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.177 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.822 ms/op
     p(99.9900) =     13.640 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
Iteration   1: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.335 ms/op
                 listUser·p0.9999: 10.551 ms/op
                 listUser·p1.00:   11.010 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.190 ms/op
                 listUser·p0.9999: 13.468 ms/op
                 listUser·p1.00:   15.139 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.860 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.326 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323542
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 100677 
    [ 2.500,  3.750) = 187076 
    [ 3.750,  5.000) = 28833 
    [ 5.000,  6.250) = 5550 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.616 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.570 ± 1.425  ops/ms
ClientPb.existUser                       thrpt       3  13.288 ± 1.268  ops/ms
ClientPb.getUser                         thrpt       3  12.964 ± 0.682  ops/ms
ClientPb.listUser                        thrpt       3  10.702 ± 0.633  ops/ms
ClientPb.createUser                       avgt       3   2.543 ± 0.366   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.259   ms/op
ClientPb.getUser                          avgt       3   2.434 ± 0.066   ms/op
ClientPb.listUser                         avgt       3   2.981 ± 0.169   ms/op
ClientPb.createUser                     sample  383050   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.516           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.245           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.761           ms/op
ClientPb.existUser                      sample  396923   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.309           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  384546   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.793           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.177           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.822           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.811           ms/op
ClientPb.listUser                       sample  323542   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.820           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.139           ms/op
