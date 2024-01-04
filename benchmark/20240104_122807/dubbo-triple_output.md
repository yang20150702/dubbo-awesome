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
# Warmup Iteration   1: 5.038 ops/ms
# Warmup Iteration   2: 12.124 ops/ms
# Warmup Iteration   3: 12.069 ops/ms
Iteration   1: 12.369 ops/ms
Iteration   2: 12.306 ops/ms
Iteration   3: 12.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.351 ±(99.9%) 0.716 ops/ms [Average]
  (min, avg, max) = (12.306, 12.351, 12.379), stdev = 0.039
  CI (99.9%): [11.636, 13.067] (assumes normal distribution)


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
# Warmup Iteration   1: 8.179 ops/ms
# Warmup Iteration   2: 13.033 ops/ms
# Warmup Iteration   3: 12.825 ops/ms
Iteration   1: 12.948 ops/ms
Iteration   2: 12.840 ops/ms
Iteration   3: 13.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.946 ±(99.9%) 1.897 ops/ms [Average]
  (min, avg, max) = (12.840, 12.946, 13.048), stdev = 0.104
  CI (99.9%): [11.048, 14.843] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.586 ops/ms
Iteration   1: 12.574 ops/ms
Iteration   2: 12.561 ops/ms
Iteration   3: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.613 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (12.561, 12.613, 12.704), stdev = 0.079
  CI (99.9%): [11.172, 14.054] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.514 ops/ms
# Warmup Iteration   2: 10.552 ops/ms
# Warmup Iteration   3: 10.654 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.656 ±(99.9%) 0.388 ops/ms [Average]
  (min, avg, max) = (10.636, 10.656, 10.679), stdev = 0.021
  CI (99.9%): [10.268, 11.044] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
Iteration   3: 2.575 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.576 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.558, 2.576, 2.594), stdev = 0.018
  CI (99.9%): [2.250, 2.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.460, 2.477, 2.487), stdev = 0.014
  CI (99.9%): [2.213, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
Iteration   3: 2.518 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.518, 2.528, 2.537), stdev = 0.009
  CI (99.9%): [2.355, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.053 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.038, 3.053, 3.061), stdev = 0.013
  CI (99.9%): [2.824, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.572 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  8.817 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 11.773 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379936
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 183599 
    [ 2.500,  3.750) = 192755 
    [ 3.750,  5.000) = 2823 
    [ 5.000,  6.250) = 296 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.709 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.388 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.601 ms/op
                 existUser·p0.9999: 13.546 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 14.385 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  8.669 ms/op
                 existUser·p0.9999: 11.125 ms/op
                 existUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389951
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 194345 
    [ 2.500,  3.750) = 191026 
    [ 3.750,  5.000) = 3642 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      6.449 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.531 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  11.798 ms/op
                 getUser·p0.9999: 13.635 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.120 ms/op
                 getUser·p0.9999: 13.359 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 11.559 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381905
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 188909 
    [ 2.500,  3.750) = 187995 
    [ 3.750,  5.000) = 3934 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      7.950 ms/op
     p(99.9900) =     13.350 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.692 ms/op
                 listUser·p0.999:  8.793 ms/op
                 listUser·p0.9999: 10.996 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.656 ms/op
                 listUser·p0.9999: 11.029 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   3.004 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.239 ms/op
                 listUser·p0.9999: 11.683 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314534
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 84497 
    [ 2.500,  3.750) = 189102 
    [ 3.750,  5.000) = 33376 
    [ 5.000,  6.250) = 6071 
    [ 6.250,  7.500) = 741 
    [ 7.500,  8.750) = 265 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.330 ms/op
     p(99.9900) =     11.281 ms/op
     p(99.9990) =     11.810 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.351 ± 0.716  ops/ms
ClientPb.existUser                       thrpt       3  12.946 ± 1.897  ops/ms
ClientPb.getUser                         thrpt       3  12.613 ± 1.441  ops/ms
ClientPb.listUser                        thrpt       3  10.656 ± 0.388  ops/ms
ClientPb.createUser                       avgt       3   2.576 ± 0.326   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.264   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.173   ms/op
ClientPb.listUser                         avgt       3   3.053 ± 0.229   ms/op
ClientPb.createUser                     sample  379936   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.781           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.709           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.565           ms/op
ClientPb.existUser                      sample  389951   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.449           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  381905   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.627           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.350           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.549           ms/op
ClientPb.listUser                       sample  314534   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.330           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
