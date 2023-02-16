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
# Warmup Iteration   1: 2.430 ops/ms
# Warmup Iteration   2: 5.539 ops/ms
# Warmup Iteration   3: 6.921 ops/ms
Iteration   1: 7.085 ops/ms
Iteration   2: 7.133 ops/ms
Iteration   3: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.114 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (7.085, 7.114, 7.133), stdev = 0.026
  CI (99.9%): [6.649, 7.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ops/ms
# Warmup Iteration   2: 6.925 ops/ms
# Warmup Iteration   3: 7.179 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 7.468 ops/ms
Iteration   3: 7.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.553 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (7.468, 7.553, 7.667), stdev = 0.103
  CI (99.9%): [5.673, 9.433] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.273 ops/ms
# Warmup Iteration   2: 6.414 ops/ms
# Warmup Iteration   3: 6.983 ops/ms
Iteration   1: 6.906 ops/ms
Iteration   2: 6.999 ops/ms
Iteration   3: 7.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.020 ±(99.9%) 2.296 ops/ms [Average]
  (min, avg, max) = (6.906, 7.020, 7.155), stdev = 0.126
  CI (99.9%): [4.723, 9.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ops/ms
# Warmup Iteration   2: 5.175 ops/ms
# Warmup Iteration   3: 5.573 ops/ms
Iteration   1: 5.758 ops/ms
Iteration   2: 5.653 ops/ms
Iteration   3: 5.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.743 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (5.653, 5.743, 5.819), stdev = 0.084
  CI (99.9%): [4.215, 7.272] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.669 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.490 ±(99.9%) 0.002 ms/op
Iteration   1: 4.452 ±(99.9%) 0.003 ms/op
Iteration   2: 4.569 ±(99.9%) 0.004 ms/op
Iteration   3: 4.575 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.532 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (4.452, 4.532, 4.575), stdev = 0.070
  CI (99.9%): [3.262, 5.802] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.175 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.359 ±(99.9%) 0.003 ms/op
Iteration   1: 4.276 ±(99.9%) 0.004 ms/op
Iteration   2: 4.339 ±(99.9%) 0.003 ms/op
Iteration   3: 4.346 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.320 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (4.276, 4.320, 4.346), stdev = 0.039
  CI (99.9%): [3.614, 5.026] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.506 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.655 ±(99.9%) 0.004 ms/op
Iteration   1: 4.434 ±(99.9%) 0.004 ms/op
Iteration   2: 4.651 ±(99.9%) 0.009 ms/op
Iteration   3: 4.718 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.601 ±(99.9%) 2.711 ms/op [Average]
  (min, avg, max) = (4.434, 4.601, 4.718), stdev = 0.149
  CI (99.9%): [1.890, 7.312] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.578 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.027 ms/op
Iteration   1: 5.790 ±(99.9%) 0.026 ms/op
Iteration   2: 5.556 ±(99.9%) 0.012 ms/op
Iteration   3: 5.488 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.611 ±(99.9%) 2.885 ms/op [Average]
  (min, avg, max) = (5.488, 5.611, 5.790), stdev = 0.158
  CI (99.9%): [2.726, 8.497] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.534 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.014 ms/op
Iteration   1: 4.678 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  13.512 ms/op
                 createUser·p0.9999: 26.876 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   2: 4.512 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  13.450 ms/op
                 createUser·p0.9999: 32.962 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 4.602 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.250 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  13.811 ms/op
                 createUser·p0.9999: 32.412 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 208835
  mean =      4.596 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5108 
    [ 2.500,  5.000) = 136530 
    [ 5.000,  7.500) = 65632 
    [ 7.500, 10.000) = 1079 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     32.542 ms/op
     p(99.9990) =     33.227 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.267 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.013 ms/op
Iteration   1: 4.378 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   6.778 ms/op
                 existUser·p0.999:  10.010 ms/op
                 existUser·p0.9999: 18.998 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 4.220 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  10.044 ms/op
                 existUser·p0.9999: 18.574 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 4.397 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   5.972 ms/op
                 existUser·p0.99:   6.892 ms/op
                 existUser·p0.999:  11.812 ms/op
                 existUser·p0.9999: 21.576 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221621
  mean =      4.330 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9659 
    [ 2.500,  5.000) = 160108 
    [ 5.000,  7.500) = 50833 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     10.685 ms/op
     p(99.9900) =     19.033 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.966 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.601 ±(99.9%) 0.013 ms/op
Iteration   1: 4.551 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  16.392 ms/op
                 getUser·p0.9999: 26.540 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 4.496 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  10.823 ms/op
                 getUser·p0.9999: 25.683 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 4.561 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  10.332 ms/op
                 getUser·p0.9999: 27.818 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 211476
  mean =      4.536 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3744 
    [ 2.500,  5.000) = 148606 
    [ 5.000,  7.500) = 57522 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     11.305 ms/op
     p(99.9900) =     27.019 ms/op
     p(99.9990) =     30.452 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.231 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.020 ms/op
Iteration   1: 5.802 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 19.955 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 5.591 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 24.057 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 5.608 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.324 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.159 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 22.227 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169391
  mean =      5.665 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 51924 
    [ 5.000,  7.500) = 102733 
    [ 7.500, 10.000) = 12773 
    [10.000, 12.500) = 1477 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     22.290 ms/op
     p(99.9990) =     24.694 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.114 ± 0.465  ops/ms
ClientGrpc.existUser                       thrpt       3   7.553 ± 1.880  ops/ms
ClientGrpc.getUser                         thrpt       3   7.020 ± 2.296  ops/ms
ClientGrpc.listUser                        thrpt       3   5.743 ± 1.528  ops/ms
ClientGrpc.createUser                       avgt       3   4.532 ± 1.270   ms/op
ClientGrpc.existUser                        avgt       3   4.320 ± 0.706   ms/op
ClientGrpc.getUser                          avgt       3   4.601 ± 2.711   ms/op
ClientGrpc.listUser                         avgt       3   5.611 ± 2.885   ms/op
ClientGrpc.createUser                     sample  208835   4.596 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.100           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.135           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.681           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.542           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.391           ms/op
ClientGrpc.existUser                      sample  221621   4.330 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.049           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.546           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.685           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.033           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.134           ms/op
ClientGrpc.getUser                        sample  211476   4.536 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.839           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.644           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.988           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.305           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.019           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.540           ms/op
ClientGrpc.listUser                       sample  169391   5.665 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.391           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.290           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.740           ms/op
