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
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 5.811 ops/ms
# Warmup Iteration   3: 7.356 ops/ms
Iteration   1: 7.502 ops/ms
Iteration   2: 7.777 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.693 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (7.502, 7.693, 7.799), stdev = 0.166
  CI (99.9%): [4.670, 10.715] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.067 ops/ms
# Warmup Iteration   2: 7.583 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.376 ops/ms
Iteration   3: 8.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.359 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (8.320, 8.359, 8.382), stdev = 0.034
  CI (99.9%): [7.737, 8.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ops/ms
# Warmup Iteration   2: 7.350 ops/ms
# Warmup Iteration   3: 7.663 ops/ms
Iteration   1: 7.593 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.833 ±(99.9%) 3.801 ops/ms [Average]
  (min, avg, max) = (7.593, 7.833, 7.968), stdev = 0.208
  CI (99.9%): [4.032, 11.633] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ops/ms
# Warmup Iteration   2: 5.562 ops/ms
# Warmup Iteration   3: 5.931 ops/ms
Iteration   1: 6.009 ops/ms
Iteration   2: 6.126 ops/ms
Iteration   3: 5.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.926 ±(99.9%) 4.582 ops/ms [Average]
  (min, avg, max) = (5.644, 5.926, 6.126), stdev = 0.251
  CI (99.9%): [1.344, 10.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.064 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.408 ±(99.9%) 0.014 ms/op
Iteration   1: 4.078 ±(99.9%) 0.004 ms/op
Iteration   2: 4.096 ±(99.9%) 0.004 ms/op
Iteration   3: 4.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.064 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (4.019, 4.064, 4.096), stdev = 0.040
  CI (99.9%): [3.331, 4.798] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.129 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.005 ms/op
Iteration   1: 3.934 ±(99.9%) 0.003 ms/op
Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
Iteration   3: 3.908 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.927 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.908, 3.927, 3.939), stdev = 0.017
  CI (99.9%): [3.622, 4.231] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.003 ms/op
Iteration   1: 4.098 ±(99.9%) 0.003 ms/op
Iteration   2: 4.097 ±(99.9%) 0.005 ms/op
Iteration   3: 4.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.085 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (4.059, 4.085, 4.098), stdev = 0.022
  CI (99.9%): [3.679, 4.491] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.426 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.536 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.017 ms/op
Iteration   1: 5.062 ±(99.9%) 0.011 ms/op
Iteration   2: 5.063 ±(99.9%) 0.021 ms/op
Iteration   3: 5.024 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.049 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (5.024, 5.049, 5.063), stdev = 0.022
  CI (99.9%): [4.639, 5.459] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.630 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.010 ms/op
Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  12.117 ms/op
                 createUser·p0.9999: 23.813 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  16.905 ms/op
                 createUser·p0.9999: 20.843 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.993 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  12.581 ms/op
                 createUser·p0.9999: 32.408 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 241124
  mean =      3.979 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5398 
    [ 2.500,  5.000) = 217343 
    [ 5.000,  7.500) = 16122 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.581 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.623 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.687 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.011 ms/op
Iteration   1: 3.695 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   18.514 ms/op

Iteration   2: 3.794 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 16.960 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.867 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.840 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  13.520 ms/op
                 existUser·p0.9999: 21.346 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253678
  mean =      3.784 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9997 
    [ 2.500,  5.000) = 228996 
    [ 5.000,  7.500) = 12998 
    [ 7.500, 10.000) = 1321 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     10.917 ms/op
     p(99.9900) =     19.178 ms/op
     p(99.9990) =     21.511 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.956 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.173 ms/op
                 getUser·p0.999:  13.631 ms/op
                 getUser·p0.9999: 16.448 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 4.156 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.987 ms/op
                 getUser·p0.999:  11.321 ms/op
                 getUser·p0.9999: 17.878 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.380 ms/op
                 getUser·p0.999:  10.710 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237815
  mean =      4.037 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5064 
    [ 2.500,  5.000) = 211341 
    [ 5.000,  7.500) = 18980 
    [ 7.500, 10.000) = 1884 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.278 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.028 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 7.380 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.543 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.020 ms/op
Iteration   1: 5.134 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  23.507 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 5.123 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 22.222 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 5.062 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  21.944 ms/op
                 listUser·p0.9999: 32.135 ms/op
                 listUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187923
  mean =      5.106 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 233 
    [ 2.500,  5.000) = 116895 
    [ 5.000,  7.500) = 59931 
    [ 7.500, 10.000) = 8971 
    [10.000, 12.500) = 1380 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     20.845 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     32.788 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.693 ± 3.023  ops/ms
ClientGrpc.existUser                       thrpt       3   8.359 ± 0.622  ops/ms
ClientGrpc.getUser                         thrpt       3   7.833 ± 3.801  ops/ms
ClientGrpc.listUser                        thrpt       3   5.926 ± 4.582  ops/ms
ClientGrpc.createUser                       avgt       3   4.064 ± 0.733   ms/op
ClientGrpc.existUser                        avgt       3   3.927 ± 0.304   ms/op
ClientGrpc.getUser                          avgt       3   4.085 ± 0.406   ms/op
ClientGrpc.listUser                         avgt       3   5.049 ± 0.410   ms/op
ClientGrpc.createUser                     sample  241124   3.979 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.932           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.348           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.581           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.113           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.702           ms/op
ClientGrpc.existUser                      sample  253678   3.784 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.917           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.178           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  237815   4.037 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.963           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.940           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.399           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.278           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.398           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  187923   5.106 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.857           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.845           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.687           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.932           ms/op
