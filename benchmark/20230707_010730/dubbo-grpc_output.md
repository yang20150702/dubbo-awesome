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
# Warmup Iteration   1: 3.016 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 8.189 ops/ms
Iteration   1: 8.605 ops/ms
Iteration   2: 8.692 ops/ms
Iteration   3: 8.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.649 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (8.605, 8.649, 8.692), stdev = 0.043
  CI (99.9%): [7.859, 9.439] (assumes normal distribution)


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
# Warmup Iteration   1: 6.039 ops/ms
# Warmup Iteration   2: 8.458 ops/ms
# Warmup Iteration   3: 8.888 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.184 ops/ms
Iteration   3: 8.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.090 ±(99.9%) 3.142 ops/ms [Average]
  (min, avg, max) = (8.891, 9.090, 9.194), stdev = 0.172
  CI (99.9%): [5.948, 12.231] (assumes normal distribution)


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
# Warmup Iteration   1: 5.226 ops/ms
# Warmup Iteration   2: 8.207 ops/ms
# Warmup Iteration   3: 8.574 ops/ms
Iteration   1: 8.604 ops/ms
Iteration   2: 8.533 ops/ms
Iteration   3: 8.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.567 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (8.533, 8.567, 8.604), stdev = 0.036
  CI (99.9%): [7.915, 9.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 6.661 ops/ms
Iteration   2: 6.863 ops/ms
Iteration   3: 6.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.716 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (6.623, 6.716, 6.863), stdev = 0.129
  CI (99.9%): [4.362, 9.070] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.438 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.009 ms/op
Iteration   1: 3.707 ±(99.9%) 0.004 ms/op
Iteration   2: 3.641 ±(99.9%) 0.004 ms/op
Iteration   3: 3.704 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.684 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.641, 3.684, 3.707), stdev = 0.037
  CI (99.9%): [3.007, 4.361] (assumes normal distribution)


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
# Warmup Iteration   1: 4.949 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.539 ±(99.9%) 0.004 ms/op
Iteration   2: 3.629 ±(99.9%) 0.004 ms/op
Iteration   3: 3.571 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.579 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.539, 3.579, 3.629), stdev = 0.046
  CI (99.9%): [2.741, 4.418] (assumes normal distribution)


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
# Warmup Iteration   1: 5.219 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.004 ms/op
Iteration   1: 3.742 ±(99.9%) 0.003 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.700 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.736 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.700, 3.736, 3.768), stdev = 0.034
  CI (99.9%): [3.108, 4.365] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.012 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.875 ±(99.9%) 0.009 ms/op
Iteration   1: 4.702 ±(99.9%) 0.009 ms/op
Iteration   2: 4.758 ±(99.9%) 0.009 ms/op
Iteration   3: 4.832 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.764 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (4.702, 4.764, 4.832), stdev = 0.065
  CI (99.9%): [3.569, 5.959] (assumes normal distribution)


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.010 ms/op
Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  12.458 ms/op
                 createUser·p0.9999: 18.910 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.122 ms/op
                 createUser·p0.999:  10.671 ms/op
                 createUser·p0.9999: 15.308 ms/op
                 createUser·p1.00:   16.024 ms/op

Iteration   3: 3.767 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  11.255 ms/op
                 createUser·p0.9999: 18.647 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255937
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7361 
    [ 2.500,  5.000) = 238095 
    [ 5.000,  7.500) = 9387 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     11.290 ms/op
     p(99.9900) =     18.508 ms/op
     p(99.9990) =     20.031 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.007 ms/op
Iteration   1: 3.564 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   2: 3.562 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.443 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  8.444 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.007 ms/op

Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.679 ms/op
                 existUser·p0.999:  8.269 ms/op
                 existUser·p0.9999: 20.413 ms/op
                 existUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270125
  mean =      3.554 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11622 
    [ 2.500,  5.000) = 252602 
    [ 5.000,  7.500) = 5329 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      8.346 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     21.217 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.010 ms/op
Iteration   1: 3.837 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  12.905 ms/op
                 getUser·p0.9999: 15.477 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   2: 3.875 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  13.119 ms/op
                 getUser·p0.9999: 17.498 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 3.716 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  9.484 ms/op
                 getUser·p0.9999: 33.108 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252055
  mean =      3.808 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4994 
    [ 2.500,  5.000) = 236916 
    [ 5.000,  7.500) = 9142 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     32.565 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 6.815 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.216 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.722 ±(99.9%) 0.016 ms/op
Iteration   1: 4.927 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.035 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 26.297 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 4.771 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  20.939 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 4.692 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.376 ms/op
                 listUser·p0.999:  20.672 ms/op
                 listUser·p0.9999: 22.339 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200108
  mean =      4.795 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 508 
    [ 2.500,  5.000) = 147411 
    [ 5.000,  7.500) = 45583 
    [ 7.500, 10.000) = 5612 
    [10.000, 12.500) = 615 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     18.248 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.649 ± 0.790  ops/ms
ClientGrpc.existUser                       thrpt       3   9.090 ± 3.142  ops/ms
ClientGrpc.getUser                         thrpt       3   8.567 ± 0.652  ops/ms
ClientGrpc.listUser                        thrpt       3   6.716 ± 2.354  ops/ms
ClientGrpc.createUser                       avgt       3   3.684 ± 0.677   ms/op
ClientGrpc.existUser                        avgt       3   3.579 ± 0.839   ms/op
ClientGrpc.getUser                          avgt       3   3.736 ± 0.629   ms/op
ClientGrpc.listUser                         avgt       3   4.764 ± 1.195   ms/op
ClientGrpc.createUser                     sample  255937   3.745 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.932           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.201           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.508           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.393           ms/op
ClientGrpc.existUser                      sample  270125   3.554 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.879           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.346           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.561           ms/op
ClientGrpc.getUser                        sample  252055   3.808 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.000           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.169           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.648           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.565           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.079           ms/op
ClientGrpc.listUser                       sample  200108   4.795 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.204           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.248           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.231           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
