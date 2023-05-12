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
# Warmup Iteration   1: 3.346 ops/ms
# Warmup Iteration   2: 7.069 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 8.773 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 8.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.888 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (8.773, 8.888, 8.959), stdev = 0.101
  CI (99.9%): [7.047, 10.728] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 9.303 ops/ms
Iteration   1: 9.539 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.435 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (9.375, 9.435, 9.539), stdev = 0.091
  CI (99.9%): [7.779, 11.091] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.303 ops/ms
# Warmup Iteration   2: 8.351 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 9.067 ops/ms
Iteration   2: 8.831 ops/ms
Iteration   3: 8.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.938 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (8.831, 8.938, 9.067), stdev = 0.120
  CI (99.9%): [6.751, 11.124] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.575 ops/ms
# Warmup Iteration   2: 6.354 ops/ms
# Warmup Iteration   3: 6.928 ops/ms
Iteration   1: 6.942 ops/ms
Iteration   2: 6.939 ops/ms
Iteration   3: 6.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.936 ±(99.9%) 0.155 ops/ms [Average]
  (min, avg, max) = (6.926, 6.936, 6.942), stdev = 0.008
  CI (99.9%): [6.781, 7.090] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.996 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.007 ms/op
Iteration   1: 3.570 ±(99.9%) 0.004 ms/op
Iteration   2: 3.597 ±(99.9%) 0.003 ms/op
Iteration   3: 3.587 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.584 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.570, 3.584, 3.597), stdev = 0.014
  CI (99.9%): [3.337, 3.832] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.146 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.003 ms/op
Iteration   1: 3.436 ±(99.9%) 0.003 ms/op
Iteration   2: 3.378 ±(99.9%) 0.003 ms/op
Iteration   3: 3.393 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.402 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.378, 3.402, 3.436), stdev = 0.030
  CI (99.9%): [2.848, 3.957] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.185 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.004 ms/op
Iteration   1: 3.575 ±(99.9%) 0.004 ms/op
Iteration   2: 3.610 ±(99.9%) 0.003 ms/op
Iteration   3: 3.592 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.592 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.575, 3.592, 3.610), stdev = 0.018
  CI (99.9%): [3.269, 3.916] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.310 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.779 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.612 ±(99.9%) 0.016 ms/op
Iteration   1: 4.631 ±(99.9%) 0.012 ms/op
Iteration   2: 4.579 ±(99.9%) 0.012 ms/op
Iteration   3: 4.553 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.588 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (4.553, 4.588, 4.631), stdev = 0.040
  CI (99.9%): [3.867, 5.309] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
Iteration   1: 3.617 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.461 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 15.116 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 3.619 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 17.509 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   3: 3.621 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  19.518 ms/op
                 createUser·p0.9999: 28.612 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265202
  mean =      3.619 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6829 
    [ 2.500,  5.000) = 254170 
    [ 5.000,  7.500) = 3720 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     10.627 ms/op
     p(99.9900) =     27.934 ms/op
     p(99.9990) =     28.891 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.794 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.007 ms/op
Iteration   1: 3.446 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  7.808 ms/op
                 existUser·p0.9999: 14.664 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 3.439 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.154 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 16.604 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  8.558 ms/op
                 existUser·p0.9999: 32.521 ms/op
                 existUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281242
  mean =      3.413 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8831 
    [ 2.500,  5.000) = 269574 
    [ 5.000,  7.500) = 2411 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     32.715 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.008 ms/op
Iteration   1: 3.595 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  10.618 ms/op
                 getUser·p0.9999: 13.981 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 3.480 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  7.471 ms/op
                 getUser·p0.9999: 16.070 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 3.528 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 32.536 ms/op
                 getUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 271555
  mean =      3.534 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8289 
    [ 2.500,  5.000) = 259566 
    [ 5.000,  7.500) = 3293 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =      8.323 ms/op
     p(99.9900) =     31.578 ms/op
     p(99.9990) =     33.105 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 7.208 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.986 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.015 ms/op
Iteration   1: 4.659 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  14.315 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.617 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.914 ms/op
                 listUser·p0.9999: 24.117 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 4.587 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  18.950 ms/op
                 listUser·p0.9999: 22.776 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207575
  mean =      4.621 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 344 
    [ 2.500,  5.000) = 171445 
    [ 5.000,  7.500) = 31982 
    [ 7.500, 10.000) = 3363 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     17.414 ms/op
     p(99.9900) =     23.634 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.888 ± 1.841  ops/ms
ClientGrpc.existUser                       thrpt       3   9.435 ± 1.656  ops/ms
ClientGrpc.getUser                         thrpt       3   8.938 ± 2.186  ops/ms
ClientGrpc.listUser                        thrpt       3   6.936 ± 0.155  ops/ms
ClientGrpc.createUser                       avgt       3   3.584 ± 0.247   ms/op
ClientGrpc.existUser                        avgt       3   3.402 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.592 ± 0.324   ms/op
ClientGrpc.listUser                         avgt       3   4.588 ± 0.721   ms/op
ClientGrpc.createUser                     sample  265202   3.619 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.821           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.627           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.934           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.000           ms/op
ClientGrpc.existUser                      sample  281242   3.413 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.652           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.064           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.801           ms/op
ClientGrpc.getUser                        sample  271555   3.534 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.323           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.578           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.128           ms/op
ClientGrpc.listUser                       sample  207575   4.621 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.414           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.634           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
