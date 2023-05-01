# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.732 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.719 ±(99.9%) 0.447 ops/ms [Average]
  (min, avg, max) = (10.691, 10.719, 10.735), stdev = 0.025
  CI (99.9%): [10.272, 11.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 10.999 ops/ms
# Warmup Iteration   3: 11.096 ops/ms
Iteration   1: 11.334 ops/ms
Iteration   2: 11.318 ops/ms
Iteration   3: 11.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.346 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (11.318, 11.346, 11.385), stdev = 0.035
  CI (99.9%): [10.702, 11.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.450 ops/ms
# Warmup Iteration   2: 10.539 ops/ms
# Warmup Iteration   3: 10.690 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.806 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (10.735, 10.806, 10.878), stdev = 0.071
  CI (99.9%): [9.503, 12.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.118 ops/ms
# Warmup Iteration   2: 7.994 ops/ms
# Warmup Iteration   3: 8.235 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.271 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.273 ±(99.9%) 0.942 ops/ms [Average]
  (min, avg, max) = (8.223, 8.273, 8.326), stdev = 0.052
  CI (99.9%): [7.331, 9.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 2.962 ±(99.9%) 0.009 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.962 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.939, 2.962, 2.984), stdev = 0.023
  CI (99.9%): [2.546, 3.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.003 ms/op
Iteration   1: 2.882 ±(99.9%) 0.003 ms/op
Iteration   2: 2.777 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (2.777, 2.836, 2.882), stdev = 0.054
  CI (99.9%): [1.850, 3.823] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.004 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.961 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.960 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.954, 2.960, 2.965), stdev = 0.006
  CI (99.9%): [2.850, 3.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.013 ms/op
Iteration   1: 3.792 ±(99.9%) 0.019 ms/op
Iteration   2: 3.843 ±(99.9%) 0.007 ms/op
Iteration   3: 3.829 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.821 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.792, 3.821, 3.843), stdev = 0.027
  CI (99.9%): [3.332, 4.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.923 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.382 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  6.801 ms/op
                 createUser·p0.9999: 13.501 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   2: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.534 ms/op
                 createUser·p0.9999: 20.470 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 2.940 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  6.886 ms/op
                 createUser·p0.9999: 16.382 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323848
  mean =      2.963 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32220 
    [ 2.500,  5.000) = 290595 
    [ 5.000,  7.500) = 675 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.199 ms/op
     p(99.9900) =     19.063 ms/op
     p(99.9990) =     21.989 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
Iteration   1: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 16.432 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   2: 2.859 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 16.033 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.538 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  5.819 ms/op
                 existUser·p0.9999: 26.609 ms/op
                 existUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334163
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53991 
    [ 2.500,  5.000) = 279158 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     16.947 ms/op
     p(99.9990) =     27.000 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.027 ms/op
                 getUser·p0.9999: 12.490 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.560 ms/op
                 getUser·p0.9999: 14.937 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.437 ms/op
                 getUser·p0.9999: 15.468 ms/op
                 getUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318399
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 911 
    [ 1.250,  2.500) = 22659 
    [ 2.500,  3.750) = 279400 
    [ 3.750,  5.000) = 14130 
    [ 5.000,  6.250) = 846 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.181 ms/op
     p(99.9900) =     14.781 ms/op
     p(99.9990) =     16.290 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.971 ms/op
                 listUser·p0.9999: 18.230 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  14.550 ms/op
                 listUser·p0.9999: 16.846 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.850 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.558 ms/op
                 listUser·p0.9999: 20.026 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249491
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6136 
    [ 2.500,  5.000) = 221264 
    [ 5.000,  7.500) = 21014 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.557 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     14.033 ms/op
     p(99.9900) =     17.993 ms/op
     p(99.9990) =     20.759 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.719 ± 0.447  ops/ms
ClientGrpc.existUser                       thrpt       3  11.346 ± 0.643  ops/ms
ClientGrpc.getUser                         thrpt       3  10.806 ± 1.303  ops/ms
ClientGrpc.listUser                        thrpt       3   8.273 ± 0.942  ops/ms
ClientGrpc.createUser                       avgt       3   2.962 ± 0.416   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.986   ms/op
ClientGrpc.getUser                          avgt       3   2.960 ± 0.110   ms/op
ClientGrpc.listUser                         avgt       3   3.821 ± 0.490   ms/op
ClientGrpc.createUser                     sample  323848   2.963 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.382           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.199           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.063           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  334163   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.234           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.947           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.230           ms/op
ClientGrpc.getUser                        sample  318399   3.013 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.181           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.781           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.630           ms/op
ClientGrpc.listUser                       sample  249491   3.850 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.925           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.557           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.033           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.993           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.692           ms/op
