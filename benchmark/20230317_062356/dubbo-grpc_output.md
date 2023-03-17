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
# Warmup Iteration   1: 4.908 ops/ms
# Warmup Iteration   2: 9.510 ops/ms
# Warmup Iteration   3: 10.226 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.665 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (10.544, 10.665, 10.726), stdev = 0.105
  CI (99.9%): [8.756, 12.574] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ops/ms
# Warmup Iteration   2: 11.249 ops/ms
# Warmup Iteration   3: 11.241 ops/ms
Iteration   1: 11.372 ops/ms
Iteration   2: 11.329 ops/ms
Iteration   3: 11.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.350 ±(99.9%) 0.388 ops/ms [Average]
  (min, avg, max) = (11.329, 11.350, 11.372), stdev = 0.021
  CI (99.9%): [10.962, 11.738] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 10.857 ops/ms
Iteration   2: 10.916 ops/ms
Iteration   3: 10.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.908 ±(99.9%) 0.852 ops/ms [Average]
  (min, avg, max) = (10.857, 10.908, 10.950), stdev = 0.047
  CI (99.9%): [10.056, 11.759] (assumes normal distribution)


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
# Warmup Iteration   1: 5.997 ops/ms
# Warmup Iteration   2: 8.202 ops/ms
# Warmup Iteration   3: 8.436 ops/ms
Iteration   1: 8.230 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.271 ±(99.9%) 0.748 ops/ms [Average]
  (min, avg, max) = (8.230, 8.271, 8.312), stdev = 0.041
  CI (99.9%): [7.523, 9.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.003 ms/op
Iteration   1: 2.897 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.003 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.932 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.897, 2.932, 2.953), stdev = 0.031
  CI (99.9%): [2.373, 3.492] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.844 ±(99.9%) 0.002 ms/op
Iteration   1: 2.885 ±(99.9%) 0.002 ms/op
Iteration   2: 2.799 ±(99.9%) 0.003 ms/op
Iteration   3: 2.847 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (2.799, 2.844, 2.885), stdev = 0.043
  CI (99.9%): [2.063, 3.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.756 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.002 ms/op
Iteration   1: 3.005 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.985, 2.998, 3.005), stdev = 0.012
  CI (99.9%): [2.787, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.009 ms/op
Iteration   1: 3.716 ±(99.9%) 0.004 ms/op
Iteration   2: 3.910 ±(99.9%) 0.015 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 2.433 ms/op [Average]
  (min, avg, max) = (3.716, 3.866, 3.972), stdev = 0.133
  CI (99.9%): [1.433, 6.299] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.326 ms/op
                 createUser·p0.9999: 12.413 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.089 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.597 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320284
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25454 
    [ 2.500,  5.000) = 293743 
    [ 5.000,  7.500) = 791 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.188 ms/op
     p(99.9900) =     19.324 ms/op
     p(99.9990) =     21.515 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.934 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.005 ms/op
Iteration   1: 2.862 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 14.530 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 13.764 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.706 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  9.500 ms/op
                 existUser·p0.9999: 16.980 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 343074
  mean =      2.796 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7748 
    [ 1.250,  2.500) = 58751 
    [ 2.500,  3.750) = 263783 
    [ 3.750,  5.000) = 11659 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     15.097 ms/op
     p(99.9990) =     18.570 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.389 ms/op
                 getUser·p0.999:  7.441 ms/op
                 getUser·p0.9999: 11.899 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  5.972 ms/op
                 getUser·p0.9999: 13.427 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 14.904 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318832
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1597 
    [ 1.250,  2.500) = 21392 
    [ 2.500,  3.750) = 279385 
    [ 3.750,  5.000) = 15090 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.973 ms/op
     p(99.9900) =     14.403 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 4.930 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 15.332 ms/op
                 listUser·p1.00:   15.843 ms/op

Iteration   2: 3.921 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 23.970 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 3.965 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.407 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243109
  mean =      3.948 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4307 
    [ 2.500,  5.000) = 216396 
    [ 5.000,  7.500) = 21161 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.777 ms/op
     p(99.9900) =     26.958 ms/op
     p(99.9990) =     28.892 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.665 ± 1.909  ops/ms
ClientGrpc.existUser                       thrpt       3  11.350 ± 0.388  ops/ms
ClientGrpc.getUser                         thrpt       3  10.908 ± 0.852  ops/ms
ClientGrpc.listUser                        thrpt       3   8.271 ± 0.748  ops/ms
ClientGrpc.createUser                       avgt       3   2.932 ± 0.559   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.780   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.211   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 2.433   ms/op
ClientGrpc.createUser                     sample  320284   2.997 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.739           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.188           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.324           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.660           ms/op
ClientGrpc.existUser                      sample  343074   2.796 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.518           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.734           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.097           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  318832   3.010 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.973           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.403           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.335           ms/op
ClientGrpc.listUser                       sample  243109   3.948 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.958           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.000           ms/op
