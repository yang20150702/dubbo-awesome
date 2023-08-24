# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.662 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (10.614, 10.662, 10.723), stdev = 0.055
  CI (99.9%): [9.650, 11.675] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.360 ops/ms
# Warmup Iteration   2: 10.696 ops/ms
# Warmup Iteration   3: 11.173 ops/ms
Iteration   1: 11.150 ops/ms
Iteration   2: 11.091 ops/ms
Iteration   3: 10.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.076 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (10.987, 11.076, 11.150), stdev = 0.083
  CI (99.9%): [9.569, 12.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.046 ops/ms
# Warmup Iteration   2: 10.142 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.676 ±(99.9%) 1.225 ops/ms [Average]
  (min, avg, max) = (10.599, 10.676, 10.716), stdev = 0.067
  CI (99.9%): [9.451, 11.902] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.836 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 8.060 ops/ms
Iteration   1: 8.019 ops/ms
Iteration   2: 8.100 ops/ms
Iteration   3: 7.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.021 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (7.943, 8.021, 8.100), stdev = 0.079
  CI (99.9%): [6.580, 9.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.075 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.067, 3.075, 3.082), stdev = 0.008
  CI (99.9%): [2.934, 3.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.003 ms/op
Iteration   1: 2.864 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.004 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (2.864, 2.910, 2.988), stdev = 0.068
  CI (99.9%): [1.668, 4.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.033 ±(99.9%) 0.004 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (3.033, 3.058, 3.077), stdev = 0.023
  CI (99.9%): [2.638, 3.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.742 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.018 ms/op
Iteration   1: 3.870 ±(99.9%) 0.010 ms/op
Iteration   2: 3.958 ±(99.9%) 0.019 ms/op
Iteration   3: 3.942 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.870, 3.924, 3.958), stdev = 0.047
  CI (99.9%): [3.069, 4.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  10.108 ms/op
                 createUser·p0.9999: 13.922 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  9.955 ms/op
                 createUser·p0.9999: 14.322 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 3.002 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.603 ms/op
                 createUser·p0.999:  13.639 ms/op
                 createUser·p0.9999: 27.700 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313419
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28961 
    [ 2.500,  5.000) = 282107 
    [ 5.000,  7.500) = 1686 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     10.573 ms/op
     p(99.9900) =     27.383 ms/op
     p(99.9990) =     27.881 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.544 ms/op
                 existUser·p0.9999: 12.173 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.280 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.906 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.600 ms/op
                 existUser·p0.999:  9.089 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329627
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1449 
    [ 1.250,  2.500) = 38209 
    [ 2.500,  3.750) = 278318 
    [ 3.750,  5.000) = 9848 
    [ 5.000,  6.250) = 736 
    [ 6.250,  7.500) = 506 
    [ 7.500,  8.750) = 277 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     17.403 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.429 ms/op
                 getUser·p0.9999: 20.594 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.795 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.522 ms/op
                 getUser·p0.9999: 20.454 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319187
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31005 
    [ 2.500,  5.000) = 285722 
    [ 5.000,  7.500) = 1924 
    [ 7.500, 10.000) = 280 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     20.158 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
Iteration   1: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  20.661 ms/op
                 listUser·p0.9999: 23.426 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 25.097 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 22.574 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241484
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1856 
    [ 2.500,  5.000) = 220047 
    [ 5.000,  7.500) = 17991 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     17.220 ms/op
     p(99.9900) =     23.981 ms/op
     p(99.9990) =     25.565 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.662 ± 1.012  ops/ms
ClientGrpc.existUser                       thrpt       3  11.076 ± 1.507  ops/ms
ClientGrpc.getUser                         thrpt       3  10.676 ± 1.225  ops/ms
ClientGrpc.listUser                        thrpt       3   8.021 ± 1.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.075 ± 0.141   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 1.242   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.420   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.855   ms/op
ClientGrpc.createUser                     sample  313419   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.573           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.383           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  329627   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.761           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  319187   3.007 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.667           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.158           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.873           ms/op
ClientGrpc.listUser                       sample  241484   3.977 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.754           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.220           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.981           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
