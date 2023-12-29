# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.758 ops/ms
# Warmup Iteration   2: 11.995 ops/ms
# Warmup Iteration   3: 12.332 ops/ms
Iteration   1: 12.374 ops/ms
Iteration   2: 12.529 ops/ms
Iteration   3: 12.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.529 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (12.374, 12.529, 12.684), stdev = 0.155
  CI (99.9%): [9.699, 15.359] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.706 ops/ms
# Warmup Iteration   2: 13.041 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 13.114 ops/ms
Iteration   2: 13.149 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.129 ±(99.9%) 0.335 ops/ms [Average]
  (min, avg, max) = (13.114, 13.129, 13.149), stdev = 0.018
  CI (99.9%): [12.794, 13.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.155 ops/ms
# Warmup Iteration   2: 12.671 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.746 ops/ms
Iteration   2: 12.851 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.794 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (12.746, 12.794, 12.851), stdev = 0.053
  CI (99.9%): [11.826, 13.762] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.401 ±(99.9%) 1.423 ops/ms [Average]
  (min, avg, max) = (10.311, 10.401, 10.449), stdev = 0.078
  CI (99.9%): [8.978, 11.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.517, 2.525, 2.534), stdev = 0.009
  CI (99.9%): [2.369, 2.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.499 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.494, 2.499, 2.507), stdev = 0.007
  CI (99.9%): [2.379, 2.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.003 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.547 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.535, 2.547, 2.562), stdev = 0.014
  CI (99.9%): [2.295, 2.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.937 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
Iteration   2: 3.080 ±(99.9%) 0.005 ms/op
Iteration   3: 3.101 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.088 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (3.080, 3.088, 3.101), stdev = 0.011
  CI (99.9%): [2.887, 3.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.728 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  11.538 ms/op
                 createUser·p0.9999: 14.509 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  10.324 ms/op
                 createUser·p0.9999: 15.490 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 10.797 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375600
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 180008 
    [ 2.500,  3.750) = 190749 
    [ 3.750,  5.000) = 3815 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.354 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     15.700 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.927 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.566 ms/op
                 existUser·p0.999:  7.831 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  6.810 ms/op
                 existUser·p0.9999: 11.750 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387083
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 190533 
    [ 2.500,  3.750) = 193255 
    [ 3.750,  5.000) = 2457 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      7.476 ms/op
     p(99.9900) =     13.264 ms/op
     p(99.9990) =     13.901 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 14.565 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  10.295 ms/op
                 getUser·p0.9999: 12.943 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  8.280 ms/op
                 getUser·p0.9999: 11.452 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375725
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 183606 
    [ 2.500,  3.750) = 187501 
    [ 3.750,  5.000) = 3633 
    [ 5.000,  6.250) = 431 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     15.393 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.788 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.795 ms/op
                 listUser·p0.9999: 11.930 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.039 ms/op
                 listUser·p0.9999: 10.903 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.229 ms/op
                 listUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315524
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 85413 
    [ 2.500,  3.750) = 188913 
    [ 3.750,  5.000) = 33654 
    [ 5.000,  6.250) = 6029 
    [ 6.250,  7.500) = 717 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     11.467 ms/op
     p(99.9990) =     12.395 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.529 ± 2.830  ops/ms
ClientPb.existUser                       thrpt       3  13.129 ± 0.335  ops/ms
ClientPb.getUser                         thrpt       3  12.794 ± 0.968  ops/ms
ClientPb.listUser                        thrpt       3  10.401 ± 1.423  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.156   ms/op
ClientPb.existUser                        avgt       3   2.499 ± 0.121   ms/op
ClientPb.getUser                          avgt       3   2.547 ± 0.252   ms/op
ClientPb.listUser                         avgt       3   3.088 ± 0.201   ms/op
ClientPb.createUser                     sample  375600   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.565           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.334           ms/op
ClientPb.existUser                      sample  387083   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.004           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.476           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.264           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  375725   2.552 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.864           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.599           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.548           ms/op
ClientPb.listUser                       sample  315524   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.752           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.467           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.009           ms/op
