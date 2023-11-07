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
# Warmup Iteration   1: 4.258 ops/ms
# Warmup Iteration   2: 11.467 ops/ms
# Warmup Iteration   3: 11.899 ops/ms
Iteration   1: 12.062 ops/ms
Iteration   2: 12.199 ops/ms
Iteration   3: 12.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.186 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (12.062, 12.186, 12.297), stdev = 0.118
  CI (99.9%): [10.034, 14.337] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 12.619 ops/ms
# Warmup Iteration   3: 12.705 ops/ms
Iteration   1: 12.553 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.620 ±(99.9%) 1.471 ops/ms [Average]
  (min, avg, max) = (12.553, 12.620, 12.709), stdev = 0.081
  CI (99.9%): [11.149, 14.091] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.200 ops/ms
# Warmup Iteration   2: 11.907 ops/ms
# Warmup Iteration   3: 12.460 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.347 ops/ms
Iteration   3: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.475 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (12.347, 12.475, 12.588), stdev = 0.121
  CI (99.9%): [10.271, 14.680] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.132 ops/ms
# Warmup Iteration   2: 10.076 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.248 ops/ms
Iteration   2: 10.186 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.182 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (10.113, 10.182, 10.248), stdev = 0.068
  CI (99.9%): [8.947, 11.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.622 ±(99.9%) 0.004 ms/op
Iteration   1: 2.628 ±(99.9%) 0.005 ms/op
Iteration   2: 2.672 ±(99.9%) 0.004 ms/op
Iteration   3: 2.668 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.656 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.628, 2.656, 2.672), stdev = 0.025
  CI (99.9%): [2.208, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.461, 2.475, 2.494), stdev = 0.017
  CI (99.9%): [2.160, 2.789] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.614 ±(99.9%) 0.003 ms/op
Iteration   1: 2.581 ±(99.9%) 0.005 ms/op
Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
Iteration   3: 2.584 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.582 ±(99.9%) 0.026 ms/op [Average]
  (min, avg, max) = (2.581, 2.582, 2.584), stdev = 0.001
  CI (99.9%): [2.556, 2.608] (assumes normal distribution)


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.005 ms/op
Iteration   1: 3.117 ±(99.9%) 0.005 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.094 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.103 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.094, 3.103, 3.117), stdev = 0.013
  CI (99.9%): [2.874, 3.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.612 ±(99.9%) 0.006 ms/op
Iteration   1: 2.624 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.199 ms/op
                 createUser·p0.95:   3.371 ms/op
                 createUser·p0.99:   4.205 ms/op
                 createUser·p0.999:  12.274 ms/op
                 createUser·p0.9999: 15.201 ms/op
                 createUser·p1.00:   16.237 ms/op

Iteration   2: 2.598 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  10.830 ms/op
                 createUser·p0.9999: 15.286 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 11.479 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368381
  mean =      2.603 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 170724 
    [ 2.500,  3.750) = 191377 
    [ 3.750,  5.000) = 4897 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     14.735 ms/op
     p(99.9990) =     15.668 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  12.593 ms/op
                 existUser·p0.9999: 14.162 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  9.938 ms/op
                 existUser·p0.9999: 14.014 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.947 ms/op
                 existUser·p0.999:  7.204 ms/op
                 existUser·p0.9999: 10.788 ms/op
                 existUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378546
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 182279 
    [ 2.500,  3.750) = 191732 
    [ 3.750,  5.000) = 3649 
    [ 5.000,  6.250) = 399 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.613 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     15.031 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.440 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.082 ms/op
                 getUser·p0.999:  12.630 ms/op
                 getUser·p0.9999: 14.739 ms/op
                 getUser·p1.00:   15.499 ms/op

Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  7.377 ms/op
                 getUser·p0.9999: 17.806 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  9.549 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374504
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 180744 
    [ 2.500,  3.750) = 187699 
    [ 3.750,  5.000) = 4874 
    [ 5.000,  6.250) = 687 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.026 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =     15.483 ms/op
     p(99.9990) =     18.260 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.009 ms/op
Iteration   1: 3.130 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  9.287 ms/op
                 listUser·p0.9999: 12.052 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  9.929 ms/op
                 listUser·p0.9999: 11.780 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   3: 3.117 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 12.034 ms/op
                 listUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306283
  mean =      3.131 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 73985 
    [ 2.500,  3.750) = 183240 
    [ 3.750,  5.000) = 39253 
    [ 5.000,  6.250) = 7832 
    [ 6.250,  7.500) = 1188 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.999 ms/op
     p(99.9990) =     12.593 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.186 ± 2.151  ops/ms
ClientPb.existUser                       thrpt       3  12.620 ± 1.471  ops/ms
ClientPb.getUser                         thrpt       3  12.475 ± 2.204  ops/ms
ClientPb.listUser                        thrpt       3  10.182 ± 1.236  ops/ms
ClientPb.createUser                       avgt       3   2.656 ± 0.448   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.314   ms/op
ClientPb.getUser                          avgt       3   2.582 ± 0.026   ms/op
ClientPb.listUser                         avgt       3   3.103 ± 0.229   ms/op
ClientPb.createUser                     sample  368381   2.603 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.076           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.735           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.237           ms/op
ClientPb.existUser                      sample  378546   2.533 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.613           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.992           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.499           ms/op
ClientPb.getUser                        sample  374504   2.561 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.561           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.483           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.497           ms/op
ClientPb.listUser                       sample  306283   3.131 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.060           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.999           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
