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
# Warmup Iteration   1: 4.825 ops/ms
# Warmup Iteration   2: 12.325 ops/ms
# Warmup Iteration   3: 12.373 ops/ms
Iteration   1: 12.725 ops/ms
Iteration   2: 12.798 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.800 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (12.725, 12.800, 12.878), stdev = 0.076
  CI (99.9%): [11.406, 14.194] (assumes normal distribution)


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
# Warmup Iteration   1: 7.865 ops/ms
# Warmup Iteration   2: 13.181 ops/ms
# Warmup Iteration   3: 13.198 ops/ms
Iteration   1: 13.094 ops/ms
Iteration   2: 13.067 ops/ms
Iteration   3: 13.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.119 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (13.067, 13.119, 13.196), stdev = 0.068
  CI (99.9%): [11.875, 14.363] (assumes normal distribution)


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
# Warmup Iteration   1: 7.746 ops/ms
# Warmup Iteration   2: 12.734 ops/ms
# Warmup Iteration   3: 12.609 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.835 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (12.785, 12.835, 12.886), stdev = 0.051
  CI (99.9%): [11.913, 13.756] (assumes normal distribution)


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
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.758 ops/ms
Iteration   2: 10.725 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.731 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (10.709, 10.731, 10.758), stdev = 0.025
  CI (99.9%): [10.269, 11.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.520, 2.540, 2.569), stdev = 0.025
  CI (99.9%): [2.077, 3.003] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.415, 2.438, 2.455), stdev = 0.021
  CI (99.9%): [2.060, 2.817] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.527 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.509, 2.527, 2.541), stdev = 0.016
  CI (99.9%): [2.226, 2.828] (assumes normal distribution)


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
# Warmup Iteration   1: 5.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 3.007 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.007, 3.019, 3.032), stdev = 0.012
  CI (99.9%): [2.793, 3.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.038 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 14.176 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.502 ms/op
                 createUser·p0.999:  9.049 ms/op
                 createUser·p0.9999: 12.390 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.494 ms/op
                 createUser·p0.9999: 11.482 ms/op
                 createUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382404
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185179 
    [ 2.500,  5.000) = 196454 
    [ 5.000,  7.500) = 357 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.752 ms/op
     p(99.9900) =     13.460 ms/op
     p(99.9990) =     16.783 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.484 ms/op
                 existUser·p0.999:  6.475 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.951 ms/op
                 existUser·p0.9999: 13.564 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.626 ms/op
                 existUser·p0.9999: 11.118 ms/op
                 existUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385667
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 186201 
    [ 2.500,  3.750) = 196263 
    [ 3.750,  5.000) = 2390 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     13.409 ms/op
     p(99.9990) =     14.191 ms/op
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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  6.159 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  9.570 ms/op
                 getUser·p0.9999: 11.939 ms/op
                 getUser·p1.00:   12.845 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.095 ms/op
                 getUser·p0.999:  6.341 ms/op
                 getUser·p0.9999: 11.460 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383354
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 189419 
    [ 2.500,  3.750) = 189111 
    [ 3.750,  5.000) = 3599 
    [ 5.000,  6.250) = 769 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      6.458 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.626 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.810 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.628 ms/op
                 listUser·p0.9999: 11.065 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 12.310 ms/op
                 listUser·p1.00:   12.927 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.495 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319660
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 94706 
    [ 2.500,  3.750) = 186540 
    [ 3.750,  5.000) = 31447 
    [ 5.000,  6.250) = 5458 
    [ 6.250,  7.500) = 718 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.733 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.800 ± 1.394  ops/ms
ClientPb.existUser                       thrpt       3  13.119 ± 1.244  ops/ms
ClientPb.getUser                         thrpt       3  12.835 ± 0.922  ops/ms
ClientPb.listUser                        thrpt       3  10.731 ± 0.461  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.463   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.379   ms/op
ClientPb.getUser                          avgt       3   2.527 ± 0.301   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.226   ms/op
ClientPb.createUser                     sample  382404   2.507 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.752           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.101           ms/op
ClientPb.existUser                      sample  385667   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.409           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  383354   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.743           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.458           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.975           ms/op
ClientPb.listUser                       sample  319660   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.733           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.927           ms/op
