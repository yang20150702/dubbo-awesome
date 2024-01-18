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
# Warmup Iteration   1: 4.364 ops/ms
# Warmup Iteration   2: 11.885 ops/ms
# Warmup Iteration   3: 12.327 ops/ms
Iteration   1: 12.442 ops/ms
Iteration   2: 12.533 ops/ms
Iteration   3: 12.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.524 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (12.442, 12.524, 12.596), stdev = 0.078
  CI (99.9%): [11.103, 13.944] (assumes normal distribution)


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
# Warmup Iteration   1: 7.881 ops/ms
# Warmup Iteration   2: 12.807 ops/ms
# Warmup Iteration   3: 12.907 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.918 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (12.809, 12.918, 12.976), stdev = 0.094
  CI (99.9%): [11.195, 14.641] (assumes normal distribution)


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
# Warmup Iteration   1: 7.668 ops/ms
# Warmup Iteration   2: 12.232 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.722 ops/ms
Iteration   2: 12.752 ops/ms
Iteration   3: 12.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.756 ±(99.9%) 0.650 ops/ms [Average]
  (min, avg, max) = (12.722, 12.756, 12.793), stdev = 0.036
  CI (99.9%): [12.105, 13.406] (assumes normal distribution)


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
# Warmup Iteration   1: 6.445 ops/ms
# Warmup Iteration   2: 10.508 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.714 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.701 ±(99.9%) 0.221 ops/ms [Average]
  (min, avg, max) = (10.689, 10.701, 10.714), stdev = 0.012
  CI (99.9%): [10.480, 10.922] (assumes normal distribution)


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.582 ±(99.9%) 0.003 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.551 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.527, 2.551, 2.582), stdev = 0.028
  CI (99.9%): [2.046, 3.057] (assumes normal distribution)


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.465, 2.483, 2.496), stdev = 0.016
  CI (99.9%): [2.191, 2.775] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.495, 2.522, 2.547), stdev = 0.026
  CI (99.9%): [2.050, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
Iteration   3: 3.044 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.059 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.044, 3.059, 3.081), stdev = 0.019
  CI (99.9%): [2.712, 3.407] (assumes normal distribution)


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.764 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  11.912 ms/op
                 createUser·p0.9999: 14.402 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  9.925 ms/op
                 createUser·p0.9999: 14.442 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.669 ms/op
                 createUser·p0.9999: 11.256 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375350
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 180012 
    [ 2.500,  3.750) = 191553 
    [ 3.750,  5.000) = 2834 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     14.799 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 3.889 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  10.097 ms/op
                 existUser·p0.9999: 14.178 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.960 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384130
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 187354 
    [ 2.500,  3.750) = 192780 
    [ 3.750,  5.000) = 2831 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.674 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.568 ms/op
                 getUser·p0.9999: 14.386 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 2.568 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  9.601 ms/op
                 getUser·p0.9999: 14.869 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.627 ms/op
                 getUser·p0.9999: 11.777 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377064
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 183026 
    [ 2.500,  3.750) = 188022 
    [ 3.750,  5.000) = 4507 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.081 ms/op
     p(99.9000) =      7.462 ms/op
     p(99.9900) =     14.447 ms/op
     p(99.9990) =     15.350 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 5.053 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.198 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.755 ms/op
                 listUser·p0.9999: 11.207 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  10.322 ms/op
                 listUser·p0.9999: 11.728 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314860
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 84211 
    [ 2.500,  3.750) = 189535 
    [ 3.750,  5.000) = 34102 
    [ 5.000,  6.250) = 5627 
    [ 6.250,  7.500) = 620 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 220 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.309 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.524 ± 1.420  ops/ms
ClientPb.existUser                       thrpt       3  12.918 ± 1.723  ops/ms
ClientPb.getUser                         thrpt       3  12.756 ± 0.650  ops/ms
ClientPb.listUser                        thrpt       3  10.701 ± 0.221  ops/ms
ClientPb.createUser                       avgt       3   2.551 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.292   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.472   ms/op
ClientPb.listUser                         avgt       3   3.059 ± 0.347   ms/op
ClientPb.createUser                     sample  375350   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.205           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  384130   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.797           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.795           ms/op
ClientPb.getUser                        sample  377064   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.700           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.081           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.462           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.447           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.565           ms/op
ClientPb.listUser                       sample  314860   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
