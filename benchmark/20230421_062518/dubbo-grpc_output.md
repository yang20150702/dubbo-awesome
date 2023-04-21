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
# Warmup Iteration   1: 1.998 ops/ms
# Warmup Iteration   2: 4.607 ops/ms
# Warmup Iteration   3: 6.377 ops/ms
Iteration   1: 6.683 ops/ms
Iteration   2: 6.700 ops/ms
Iteration   3: 6.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.721 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (6.683, 6.721, 6.780), stdev = 0.052
  CI (99.9%): [5.776, 7.666] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ops/ms
# Warmup Iteration   2: 6.698 ops/ms
# Warmup Iteration   3: 7.046 ops/ms
Iteration   1: 7.448 ops/ms
Iteration   2: 7.381 ops/ms
Iteration   3: 7.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.417 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (7.381, 7.417, 7.448), stdev = 0.034
  CI (99.9%): [6.794, 8.040] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.923 ops/ms
# Warmup Iteration   2: 6.458 ops/ms
# Warmup Iteration   3: 6.972 ops/ms
Iteration   1: 6.804 ops/ms
Iteration   2: 6.978 ops/ms
Iteration   3: 7.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.952 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (6.804, 6.952, 7.073), stdev = 0.136
  CI (99.9%): [4.463, 9.440] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 4.817 ops/ms
# Warmup Iteration   3: 5.399 ops/ms
Iteration   1: 5.402 ops/ms
Iteration   2: 5.408 ops/ms
Iteration   3: 5.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.457 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (5.402, 5.457, 5.559), stdev = 0.089
  CI (99.9%): [3.832, 7.081] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.496 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.012 ms/op
Iteration   1: 4.728 ±(99.9%) 0.003 ms/op
Iteration   2: 4.838 ±(99.9%) 0.004 ms/op
Iteration   3: 4.657 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.741 ±(99.9%) 1.671 ms/op [Average]
  (min, avg, max) = (4.657, 4.741, 4.838), stdev = 0.092
  CI (99.9%): [3.070, 6.412] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.635 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.004 ms/op
Iteration   1: 4.282 ±(99.9%) 0.004 ms/op
Iteration   2: 4.255 ±(99.9%) 0.004 ms/op
Iteration   3: 4.314 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.284 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (4.255, 4.284, 4.314), stdev = 0.029
  CI (99.9%): [3.746, 4.822] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.446 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.004 ms/op
Iteration   1: 4.503 ±(99.9%) 0.003 ms/op
Iteration   2: 4.599 ±(99.9%) 0.003 ms/op
Iteration   3: 4.618 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.574 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (4.503, 4.574, 4.618), stdev = 0.062
  CI (99.9%): [3.451, 5.696] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.589 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.417 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.872 ±(99.9%) 0.016 ms/op
Iteration   1: 5.597 ±(99.9%) 0.009 ms/op
Iteration   2: 5.709 ±(99.9%) 0.015 ms/op
Iteration   3: 5.780 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.695 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (5.597, 5.695, 5.780), stdev = 0.092
  CI (99.9%): [4.013, 7.378] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.948 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.014 ms/op
Iteration   1: 4.625 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.213 ms/op
                 createUser·p0.999:  12.534 ms/op
                 createUser·p0.9999: 17.078 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 4.529 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  14.522 ms/op
                 createUser·p0.9999: 19.525 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   3: 4.565 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  13.975 ms/op
                 createUser·p0.9999: 36.438 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209838
  mean =      4.573 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3275 
    [ 2.500,  5.000) = 152181 
    [ 5.000,  7.500) = 51520 
    [ 7.500, 10.000) = 2210 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     36.563 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.568 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.505 ±(99.9%) 0.014 ms/op
Iteration   1: 4.400 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 22.592 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 4.380 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  12.237 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 4.270 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  16.593 ms/op
                 existUser·p0.9999: 34.636 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220642
  mean =      4.349 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7093 
    [ 2.500,  5.000) = 173129 
    [ 5.000,  7.500) = 37779 
    [ 7.500, 10.000) = 1995 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.779 ms/op
     p(99.9000) =     12.818 ms/op
     p(99.9900) =     32.897 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.263 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.050 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.594 ±(99.9%) 0.016 ms/op
Iteration   1: 4.559 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   8.428 ms/op
                 getUser·p0.999:  11.161 ms/op
                 getUser·p0.9999: 30.015 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 4.651 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 32.154 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   3: 4.567 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.864 ms/op
                 getUser·p0.999:  14.082 ms/op
                 getUser·p0.9999: 33.456 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208975
  mean =      4.592 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3694 
    [ 2.500,  5.000) = 151188 
    [ 5.000,  7.500) = 51012 
    [ 7.500, 10.000) = 2408 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     33.001 ms/op
     p(99.9990) =     33.739 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.161 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.473 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.021 ms/op
Iteration   1: 5.757 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  23.867 ms/op
                 listUser·p0.9999: 32.192 ms/op
                 listUser·p1.00:   32.670 ms/op

Iteration   2: 5.898 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 23.668 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   3: 5.867 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   10.835 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 26.366 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 164507
  mean =      5.840 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 45632 
    [ 5.000,  7.500) = 100077 
    [ 7.500, 10.000) = 15519 
    [10.000, 12.500) = 2435 
    [12.500, 15.000) = 387 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     32.585 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.721 ± 0.945  ops/ms
ClientGrpc.existUser                       thrpt       3   7.417 ± 0.623  ops/ms
ClientGrpc.getUser                         thrpt       3   6.952 ± 2.488  ops/ms
ClientGrpc.listUser                        thrpt       3   5.457 ± 1.625  ops/ms
ClientGrpc.createUser                       avgt       3   4.741 ± 1.671   ms/op
ClientGrpc.existUser                        avgt       3   4.284 ± 0.538   ms/op
ClientGrpc.getUser                          avgt       3   4.574 ± 1.123   ms/op
ClientGrpc.listUser                         avgt       3   5.695 ± 1.683   ms/op
ClientGrpc.createUser                     sample  209838   4.573 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.043           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.677           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.160           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.012           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.817           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.635           ms/op
ClientGrpc.existUser                      sample  220642   4.349 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.015           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.779           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.818           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.897           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.996           ms/op
ClientGrpc.getUser                        sample  208975   4.592 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.693           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.094           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.001           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.882           ms/op
ClientGrpc.listUser                       sample  164507   5.840 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.684           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.059           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.201           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.557           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.670           ms/op
