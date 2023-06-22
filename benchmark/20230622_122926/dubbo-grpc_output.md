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
# Warmup Iteration   1: 2.904 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 7.487 ops/ms
Iteration   1: 8.084 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.236 ±(99.9%) 2.774 ops/ms [Average]
  (min, avg, max) = (8.084, 8.236, 8.388), stdev = 0.152
  CI (99.9%): [5.462, 11.009] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.425 ops/ms
# Warmup Iteration   2: 7.937 ops/ms
# Warmup Iteration   3: 8.519 ops/ms
Iteration   1: 8.921 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 8.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.921 ±(99.9%) 0.089 ops/ms [Average]
  (min, avg, max) = (8.917, 8.921, 8.926), stdev = 0.005
  CI (99.9%): [8.833, 9.010] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 8.209 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.276 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (8.169, 8.276, 8.448), stdev = 0.151
  CI (99.9%): [5.522, 11.029] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ops/ms
# Warmup Iteration   2: 5.949 ops/ms
# Warmup Iteration   3: 6.263 ops/ms
Iteration   1: 6.399 ops/ms
Iteration   2: 6.625 ops/ms
Iteration   3: 6.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.504 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (6.399, 6.504, 6.625), stdev = 0.114
  CI (99.9%): [4.426, 8.581] (assumes normal distribution)


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
# Warmup Iteration   1: 5.435 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.009 ms/op
Iteration   1: 3.857 ±(99.9%) 0.003 ms/op
Iteration   2: 3.818 ±(99.9%) 0.003 ms/op
Iteration   3: 3.915 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.863 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.818, 3.863, 3.915), stdev = 0.048
  CI (99.9%): [2.979, 4.748] (assumes normal distribution)


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.005 ms/op
Iteration   1: 3.725 ±(99.9%) 0.003 ms/op
Iteration   2: 3.639 ±(99.9%) 0.003 ms/op
Iteration   3: 3.692 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.685 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.639, 3.685, 3.725), stdev = 0.044
  CI (99.9%): [2.892, 4.479] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.966 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.003 ms/op
Iteration   1: 3.787 ±(99.9%) 0.005 ms/op
Iteration   2: 3.861 ±(99.9%) 0.004 ms/op
Iteration   3: 3.860 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.836 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (3.787, 3.836, 3.861), stdev = 0.043
  CI (99.9%): [3.053, 4.619] (assumes normal distribution)


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
# Warmup Iteration   1: 7.370 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.097 ±(99.9%) 0.018 ms/op
Iteration   1: 5.092 ±(99.9%) 0.019 ms/op
Iteration   2: 5.045 ±(99.9%) 0.019 ms/op
Iteration   3: 5.026 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.054 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (5.026, 5.054, 5.092), stdev = 0.034
  CI (99.9%): [4.433, 5.676] (assumes normal distribution)


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
# Warmup Iteration   1: 5.534 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
Iteration   1: 3.836 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   7.998 ms/op
                 createUser·p0.999:  13.308 ms/op
                 createUser·p0.9999: 16.034 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.785 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 20.350 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.845 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.456 ms/op
                 createUser·p0.99:   8.112 ms/op
                 createUser·p0.999:  15.249 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 249023
  mean =      3.854 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12734 
    [ 2.500,  5.000) = 217211 
    [ 5.000,  7.500) = 15817 
    [ 7.500, 10.000) = 2551 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     22.253 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.011 ms/op
Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   7.794 ms/op
                 existUser·p0.999:  12.496 ms/op
                 existUser·p0.9999: 16.756 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 3.555 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.693 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.085 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 26.291 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 259296
  mean =      3.701 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12636 
    [ 2.500,  5.000) = 233575 
    [ 5.000,  7.500) = 10489 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     25.215 ms/op
     p(99.9990) =     26.588 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.013 ms/op
Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  12.580 ms/op
                 getUser·p0.9999: 17.424 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.354 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  13.176 ms/op
                 getUser·p0.9999: 27.833 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  11.738 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250481
  mean =      3.834 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10389 
    [ 2.500,  5.000) = 225092 
    [ 5.000,  7.500) = 12296 
    [ 7.500, 10.000) = 2012 
    [10.000, 12.500) = 422 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.653 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     28.950 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.639 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.108 ±(99.9%) 0.021 ms/op
Iteration   1: 5.118 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   7.199 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 24.395 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 5.104 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  22.622 ms/op
                 listUser·p0.9999: 28.425 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   3: 5.056 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.889 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  24.102 ms/op
                 listUser·p0.9999: 35.193 ms/op
                 listUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188471
  mean =      5.093 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1474 
    [ 2.500,  5.000) = 111966 
    [ 5.000,  7.500) = 61978 
    [ 7.500, 10.000) = 10883 
    [10.000, 12.500) = 1469 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     37.902 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.236 ± 2.774  ops/ms
ClientGrpc.existUser                       thrpt       3   8.921 ± 0.089  ops/ms
ClientGrpc.getUser                         thrpt       3   8.276 ± 2.753  ops/ms
ClientGrpc.listUser                        thrpt       3   6.504 ± 2.077  ops/ms
ClientGrpc.createUser                       avgt       3   3.863 ± 0.884   ms/op
ClientGrpc.existUser                        avgt       3   3.685 ± 0.794   ms/op
ClientGrpc.getUser                          avgt       3   3.836 ± 0.783   ms/op
ClientGrpc.listUser                         avgt       3   5.054 ± 0.622   ms/op
ClientGrpc.createUser                     sample  249023   3.854 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.830           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.971           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.253           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  259296   3.701 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.504           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.845           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.215           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  250481   3.834 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.354           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.153           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.599           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.149           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.622           ms/op
ClientGrpc.listUser                       sample  188471   5.093 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.217           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.256           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.414           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.079           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.076           ms/op
