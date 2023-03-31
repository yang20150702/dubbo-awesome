# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.292 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.692 ±(99.9%) 1.529 ops/ms [Average]
  (min, avg, max) = (10.605, 10.692, 10.772), stdev = 0.084
  CI (99.9%): [9.164, 12.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.646 ops/ms
# Warmup Iteration   2: 10.719 ops/ms
# Warmup Iteration   3: 11.301 ops/ms
Iteration   1: 11.337 ops/ms
Iteration   2: 11.251 ops/ms
Iteration   3: 11.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.335 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (11.251, 11.335, 11.418), stdev = 0.084
  CI (99.9%): [9.811, 12.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.603 ops/ms
# Warmup Iteration   2: 10.184 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.588 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.625 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (10.588, 10.625, 10.665), stdev = 0.039
  CI (99.9%): [9.917, 11.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 8.382 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 7.938 ops/ms
Iteration   2: 8.082 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.058 ±(99.9%) 2.007 ops/ms [Average]
  (min, avg, max) = (7.938, 8.058, 8.154), stdev = 0.110
  CI (99.9%): [6.051, 10.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.009 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.979 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.978 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.960, 2.978, 2.997), stdev = 0.018
  CI (99.9%): [2.646, 3.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.898 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.862 ±(99.9%) 0.002 ms/op
Iteration   3: 2.902 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (2.862, 2.903, 2.943), stdev = 0.040
  CI (99.9%): [2.165, 3.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.002 ms/op
Iteration   2: 3.001 ±(99.9%) 0.005 ms/op
Iteration   3: 2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.000 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (2.974, 3.000, 3.024), stdev = 0.025
  CI (99.9%): [2.537, 3.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.330 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.015 ms/op
Iteration   1: 3.975 ±(99.9%) 0.016 ms/op
Iteration   2: 3.933 ±(99.9%) 0.034 ms/op
Iteration   3: 3.854 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.921 ±(99.9%) 1.124 ms/op [Average]
  (min, avg, max) = (3.854, 3.921, 3.975), stdev = 0.062
  CI (99.9%): [2.797, 5.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.930 ms/op
                 createUser·p0.9999: 29.601 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.980 ms/op
                 createUser·p0.9999: 20.549 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.840 ms/op
                 createUser·p0.9999: 19.932 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322419
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24395 
    [ 2.500,  5.000) = 296750 
    [ 5.000,  7.500) = 972 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.268 ms/op
     p(99.9900) =     27.270 ms/op
     p(99.9990) =     29.779 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.577 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
Iteration   1: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.271 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.424 ms/op
                 existUser·p0.9999: 11.862 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   3: 2.874 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 24.572 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333110
  mean =      2.881 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49246 
    [ 2.500,  5.000) = 282702 
    [ 5.000,  7.500) = 810 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.576 ms/op
     p(99.9900) =     17.488 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.352 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.603 ms/op
                 getUser·p0.9999: 15.374 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.060 ms/op
                 getUser·p0.9999: 14.703 ms/op
                 getUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320250
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1271 
    [ 1.250,  2.500) = 21642 
    [ 2.500,  3.750) = 282717 
    [ 3.750,  5.000) = 13308 
    [ 5.000,  6.250) = 779 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.756 ms/op
     p(99.9900) =     18.254 ms/op
     p(99.9990) =     19.516 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
Iteration   1: 3.954 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  11.815 ms/op
                 listUser·p0.9999: 17.626 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.498 ms/op
                 listUser·p0.9999: 19.529 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.866 ms/op
                 listUser·p0.999:  13.807 ms/op
                 listUser·p0.9999: 16.809 ms/op
                 listUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241254
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 2899 
    [ 2.500,  3.750) = 95111 
    [ 3.750,  5.000) = 122566 
    [ 5.000,  6.250) = 14845 
    [ 6.250,  7.500) = 4597 
    [ 7.500,  8.750) = 591 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 108 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     13.824 ms/op
     p(99.9900) =     18.731 ms/op
     p(99.9990) =     19.811 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.692 ± 1.529  ops/ms
ClientGrpc.existUser                       thrpt       3  11.335 ± 1.524  ops/ms
ClientGrpc.getUser                         thrpt       3  10.625 ± 0.707  ops/ms
ClientGrpc.listUser                        thrpt       3   8.058 ± 2.007  ops/ms
ClientGrpc.createUser                       avgt       3   2.978 ± 0.333   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.737   ms/op
ClientGrpc.getUser                          avgt       3   3.000 ± 0.463   ms/op
ClientGrpc.listUser                         avgt       3   3.921 ± 1.124   ms/op
ClientGrpc.createUser                     sample  322419   2.977 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.570           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.961           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.420           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.268           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.270           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.852           ms/op
ClientGrpc.existUser                      sample  333110   2.881 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.512           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.576           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.488           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  320250   2.995 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.679           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.756           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.254           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  241254   3.977 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.974           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.824           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.731           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.857           ms/op
