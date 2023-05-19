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
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 5.726 ops/ms
# Warmup Iteration   3: 7.046 ops/ms
Iteration   1: 7.543 ops/ms
Iteration   2: 7.531 ops/ms
Iteration   3: 7.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.566 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (7.531, 7.566, 7.623), stdev = 0.050
  CI (99.9%): [6.656, 8.475] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ops/ms
# Warmup Iteration   2: 7.323 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 7.775 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.854 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (7.775, 7.854, 7.945), stdev = 0.086
  CI (99.9%): [6.292, 9.417] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ops/ms
# Warmup Iteration   2: 6.683 ops/ms
# Warmup Iteration   3: 7.229 ops/ms
Iteration   1: 7.333 ops/ms
Iteration   2: 7.208 ops/ms
Iteration   3: 7.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.337 ±(99.9%) 2.405 ops/ms [Average]
  (min, avg, max) = (7.208, 7.337, 7.471), stdev = 0.132
  CI (99.9%): [4.932, 9.742] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 5.152 ops/ms
# Warmup Iteration   3: 5.702 ops/ms
Iteration   1: 5.721 ops/ms
Iteration   2: 5.670 ops/ms
Iteration   3: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.745 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (5.670, 5.745, 5.845), stdev = 0.090
  CI (99.9%): [4.104, 7.386] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.563 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.401 ±(99.9%) 0.013 ms/op
Iteration   1: 4.426 ±(99.9%) 0.003 ms/op
Iteration   2: 4.402 ±(99.9%) 0.004 ms/op
Iteration   3: 4.470 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.432 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (4.402, 4.432, 4.470), stdev = 0.035
  CI (99.9%): [3.799, 5.066] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.736 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.004 ms/op
Iteration   1: 4.095 ±(99.9%) 0.003 ms/op
Iteration   2: 4.049 ±(99.9%) 0.003 ms/op
Iteration   3: 4.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.091 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (4.049, 4.091, 4.128), stdev = 0.040
  CI (99.9%): [3.369, 4.813] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.494 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.664 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.004 ms/op
Iteration   1: 4.197 ±(99.9%) 0.004 ms/op
Iteration   2: 4.221 ±(99.9%) 0.004 ms/op
Iteration   3: 4.457 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.292 ±(99.9%) 2.616 ms/op [Average]
  (min, avg, max) = (4.197, 4.292, 4.457), stdev = 0.143
  CI (99.9%): [1.676, 6.908] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.801 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.679 ±(99.9%) 0.020 ms/op
Iteration   1: 5.519 ±(99.9%) 0.015 ms/op
Iteration   2: 5.464 ±(99.9%) 0.008 ms/op
Iteration   3: 5.331 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.438 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (5.331, 5.438, 5.519), stdev = 0.096
  CI (99.9%): [3.679, 7.198] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.840 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.744 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.013 ms/op
Iteration   1: 4.390 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 15.478 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 4.223 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 4.466 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  12.540 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220278
  mean =      4.357 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2011 
    [ 2.500,  5.000) = 178571 
    [ 5.000,  7.500) = 37911 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     12.365 ms/op
     p(99.9900) =     21.036 ms/op
     p(99.9990) =     21.614 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.012 ms/op
Iteration   1: 4.212 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  12.328 ms/op
                 existUser·p0.9999: 17.171 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 16.448 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  9.759 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237777
  mean =      4.039 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6069 
    [ 2.500,  5.000) = 207615 
    [ 5.000,  7.500) = 22895 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     11.915 ms/op
     p(99.9900) =     32.874 ms/op
     p(99.9990) =     33.988 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 6.519 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.687 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.421 ±(99.9%) 0.013 ms/op
Iteration   1: 4.299 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.468 ms/op
                 getUser·p0.999:  13.830 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 4.423 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  12.337 ms/op
                 getUser·p0.9999: 18.532 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 4.527 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.152 ms/op
                 getUser·p0.99:   7.674 ms/op
                 getUser·p0.999:  11.703 ms/op
                 getUser·p0.9999: 21.690 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217418
  mean =      4.414 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2857 
    [ 2.500,  5.000) = 171310 
    [ 5.000,  7.500) = 40931 
    [ 7.500, 10.000) = 1775 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.972 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     12.494 ms/op
     p(99.9900) =     21.930 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 9.746 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 6.393 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.795 ±(99.9%) 0.021 ms/op
Iteration   1: 5.703 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.384 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  17.856 ms/op
                 listUser·p0.9999: 22.432 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 5.965 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 5.694 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  22.966 ms/op
                 listUser·p0.9999: 25.761 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165829
  mean =      5.785 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 121 
    [ 2.500,  5.000) = 47416 
    [ 5.000,  7.500) = 101867 
    [ 7.500, 10.000) = 13362 
    [10.000, 12.500) = 2111 
    [12.500, 15.000) = 532 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     21.043 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     26.150 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.566 ± 0.909  ops/ms
ClientGrpc.existUser                       thrpt       3   7.854 ± 1.562  ops/ms
ClientGrpc.getUser                         thrpt       3   7.337 ± 2.405  ops/ms
ClientGrpc.listUser                        thrpt       3   5.745 ± 1.641  ops/ms
ClientGrpc.createUser                       avgt       3   4.432 ± 0.634   ms/op
ClientGrpc.existUser                        avgt       3   4.091 ± 0.722   ms/op
ClientGrpc.getUser                          avgt       3   4.292 ± 2.616   ms/op
ClientGrpc.listUser                         avgt       3   5.438 ± 1.760   ms/op
ClientGrpc.createUser                     sample  220278   4.357 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.004           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.759           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.193           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.365           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.036           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.725           ms/op
ClientGrpc.existUser                      sample  237777   4.039 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.668           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.915           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.874           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.013           ms/op
ClientGrpc.getUser                        sample  217418   4.414 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.997           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.972           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.494           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.930           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  165829   5.785 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.846           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.487           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.043           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.445           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
