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
# Warmup Iteration   1: 4.743 ops/ms
# Warmup Iteration   2: 9.559 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.824 ops/ms
Iteration   2: 10.951 ops/ms
Iteration   3: 10.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.915 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (10.824, 10.915, 10.970), stdev = 0.080
  CI (99.9%): [9.463, 12.367] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 10.824 ops/ms
# Warmup Iteration   3: 11.260 ops/ms
Iteration   1: 11.168 ops/ms
Iteration   2: 11.488 ops/ms
Iteration   3: 11.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.351 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (11.168, 11.351, 11.488), stdev = 0.165
  CI (99.9%): [8.347, 14.355] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.459 ops/ms
# Warmup Iteration   2: 10.726 ops/ms
# Warmup Iteration   3: 10.919 ops/ms
Iteration   1: 10.884 ops/ms
Iteration   2: 10.984 ops/ms
Iteration   3: 11.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.973 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (10.884, 10.973, 11.052), stdev = 0.084
  CI (99.9%): [9.436, 12.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 8.099 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.278 ops/ms
Iteration   2: 8.502 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.363 ±(99.9%) 2.219 ops/ms [Average]
  (min, avg, max) = (8.278, 8.363, 8.502), stdev = 0.122
  CI (99.9%): [6.143, 10.582] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.004 ms/op
Iteration   1: 2.981 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.947 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (2.910, 2.947, 2.981), stdev = 0.035
  CI (99.9%): [2.304, 3.591] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.852 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.005 ms/op
Iteration   1: 2.854 ±(99.9%) 0.004 ms/op
Iteration   2: 2.829 ±(99.9%) 0.003 ms/op
Iteration   3: 2.892 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.859 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.829, 2.859, 2.892), stdev = 0.032
  CI (99.9%): [2.279, 3.438] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.948 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (2.916, 2.948, 2.985), stdev = 0.035
  CI (99.9%): [2.305, 3.590] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.015 ms/op
Iteration   1: 3.751 ±(99.9%) 0.016 ms/op
Iteration   2: 3.828 ±(99.9%) 0.016 ms/op
Iteration   3: 3.846 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.808 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.751, 3.808, 3.846), stdev = 0.050
  CI (99.9%): [2.888, 4.728] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 11.010 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.653 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.021 ms/op
                 createUser·p0.9999: 23.440 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324375
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34807 
    [ 2.500,  5.000) = 288312 
    [ 5.000,  7.500) = 950 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.321 ms/op
     p(99.9900) =     21.815 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 12.530 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   2: 2.749 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.702 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.805 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.396 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.521 ms/op
                 existUser·p0.999:  8.207 ms/op
                 existUser·p0.9999: 14.771 ms/op
                 existUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342709
  mean =      2.801 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6814 
    [ 1.250,  2.500) = 52385 
    [ 2.500,  3.750) = 273361 
    [ 3.750,  5.000) = 8893 
    [ 5.000,  6.250) = 807 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.638 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     15.472 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  5.988 ms/op
                 getUser·p0.9999: 17.828 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.895 ms/op
                 getUser·p0.9999: 12.801 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   3: 2.983 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.794 ms/op
                 getUser·p0.9999: 25.306 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324631
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29605 
    [ 2.500,  5.000) = 293811 
    [ 5.000,  7.500) = 935 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.994 ms/op
     p(99.9900) =     21.528 ms/op
     p(99.9990) =     25.977 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.011 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.120 ms/op
                 listUser·p0.9999: 17.222 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  14.561 ms/op
                 listUser·p0.9999: 22.906 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.341 ms/op
                 listUser·p0.9999: 20.324 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250087
  mean =      3.835 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4843 
    [ 2.500,  5.000) = 228073 
    [ 5.000,  7.500) = 16191 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.232 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.915 ± 1.452  ops/ms
ClientGrpc.existUser                       thrpt       3  11.351 ± 3.004  ops/ms
ClientGrpc.getUser                         thrpt       3  10.973 ± 1.537  ops/ms
ClientGrpc.listUser                        thrpt       3   8.363 ± 2.219  ops/ms
ClientGrpc.createUser                       avgt       3   2.947 ± 0.644   ms/op
ClientGrpc.existUser                        avgt       3   2.859 ± 0.580   ms/op
ClientGrpc.getUser                          avgt       3   2.948 ± 0.643   ms/op
ClientGrpc.listUser                         avgt       3   3.808 ± 0.920   ms/op
ClientGrpc.createUser                     sample  324375   2.960 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.815           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  342709   2.801 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.396           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.638           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.221           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.827           ms/op
ClientGrpc.getUser                        sample  324631   2.954 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.587           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.994           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.528           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.051           ms/op
ClientGrpc.listUser                       sample  250087   3.835 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.052           ms/op
