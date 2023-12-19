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
# Warmup Iteration   1: 4.663 ops/ms
# Warmup Iteration   2: 11.620 ops/ms
# Warmup Iteration   3: 12.024 ops/ms
Iteration   1: 12.253 ops/ms
Iteration   2: 12.408 ops/ms
Iteration   3: 12.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.375 ±(99.9%) 2.010 ops/ms [Average]
  (min, avg, max) = (12.253, 12.375, 12.465), stdev = 0.110
  CI (99.9%): [10.366, 14.385] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.634 ops/ms
# Warmup Iteration   3: 12.940 ops/ms
Iteration   1: 12.946 ops/ms
Iteration   2: 12.901 ops/ms
Iteration   3: 12.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.922 ±(99.9%) 0.411 ops/ms [Average]
  (min, avg, max) = (12.901, 12.922, 12.946), stdev = 0.023
  CI (99.9%): [12.511, 13.333] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.271 ops/ms
# Warmup Iteration   2: 12.443 ops/ms
# Warmup Iteration   3: 12.461 ops/ms
Iteration   1: 12.675 ops/ms
Iteration   2: 12.540 ops/ms
Iteration   3: 12.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.552 ±(99.9%) 2.131 ops/ms [Average]
  (min, avg, max) = (12.442, 12.552, 12.675), stdev = 0.117
  CI (99.9%): [10.421, 14.684] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.467 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.225 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.264 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.231 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (10.162, 10.231, 10.266), stdev = 0.060
  CI (99.9%): [9.140, 11.322] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.574 ±(99.9%) 0.005 ms/op
Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
Iteration   3: 2.585 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.579 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (2.574, 2.579, 2.585), stdev = 0.005
  CI (99.9%): [2.484, 2.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.546 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.530, 2.546, 2.558), stdev = 0.014
  CI (99.9%): [2.283, 2.809] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.003 ms/op
Iteration   3: 2.548 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.548, 2.553, 2.562), stdev = 0.008
  CI (99.9%): [2.405, 2.701] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
Iteration   3: 3.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.062 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (3.054, 3.062, 3.071), stdev = 0.009
  CI (99.9%): [2.905, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.729 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.006 ms/op
Iteration   1: 2.604 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.166 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 15.598 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  10.895 ms/op
                 createUser·p0.9999: 13.090 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   3: 2.584 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  5.770 ms/op
                 createUser·p0.9999: 12.026 ms/op
                 createUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371506
  mean =      2.582 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 174951 
    [ 2.500,  3.750) = 191202 
    [ 3.750,  5.000) = 4404 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      6.140 ms/op
     p(99.9900) =     14.137 ms/op
     p(99.9990) =     16.541 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.120 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  5.538 ms/op
                 existUser·p0.9999: 13.110 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 12.201 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385970
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 189868 
    [ 2.500,  3.750) = 192689 
    [ 3.750,  5.000) = 2538 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.628 ms/op
     p(99.9900) =     13.360 ms/op
     p(99.9990) =     14.198 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.613 ±(99.9%) 0.007 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 14.230 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.589 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  10.035 ms/op
                 getUser·p0.9999: 14.521 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 2.581 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.162 ms/op
                 getUser·p0.95:   3.294 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  9.281 ms/op
                 getUser·p0.9999: 12.409 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372124
  mean =      2.577 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 179353 
    [ 2.500,  3.750) = 188006 
    [ 3.750,  5.000) = 3756 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      9.796 ms/op
     p(99.9900) =     14.218 ms/op
     p(99.9990) =     14.635 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 5.202 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 12.182 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 12.606 ms/op
                 listUser·p1.00:   13.648 ms/op

Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313773
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 84011 
    [ 2.500,  3.750) = 187753 
    [ 3.750,  5.000) = 34357 
    [ 5.000,  6.250) = 6073 
    [ 6.250,  7.500) = 771 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.769 ms/op
     p(99.9900) =     12.288 ms/op
     p(99.9990) =     13.520 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.375 ± 2.010  ops/ms
ClientPb.existUser                       thrpt       3  12.922 ± 0.411  ops/ms
ClientPb.getUser                         thrpt       3  12.552 ± 2.131  ops/ms
ClientPb.listUser                        thrpt       3  10.231 ± 1.091  ops/ms
ClientPb.createUser                       avgt       3   2.579 ± 0.095   ms/op
ClientPb.existUser                        avgt       3   2.546 ± 0.263   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.148   ms/op
ClientPb.listUser                         avgt       3   3.062 ± 0.157   ms/op
ClientPb.createUser                     sample  371506   2.582 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.140           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.137           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.581           ms/op
ClientPb.existUser                      sample  385970   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.628           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.360           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.434           ms/op
ClientPb.getUser                        sample  372124   2.577 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.285           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.796           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.218           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  313773   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.854           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.769           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.648           ms/op
