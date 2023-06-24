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
# Warmup Iteration   1: 3.178 ops/ms
# Warmup Iteration   2: 6.011 ops/ms
# Warmup Iteration   3: 7.751 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.119 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (8.044, 8.119, 8.263), stdev = 0.125
  CI (99.9%): [5.847, 10.391] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.474 ops/ms
Iteration   1: 8.779 ops/ms
Iteration   2: 8.823 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.795 ±(99.9%) 0.436 ops/ms [Average]
  (min, avg, max) = (8.779, 8.795, 8.823), stdev = 0.024
  CI (99.9%): [8.359, 9.231] (assumes normal distribution)


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
# Warmup Iteration   1: 5.344 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 8.355 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.306 ±(99.9%) 2.150 ops/ms [Average]
  (min, avg, max) = (8.172, 8.306, 8.392), stdev = 0.118
  CI (99.9%): [6.156, 10.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.518 ops/ms
# Warmup Iteration   2: 5.729 ops/ms
# Warmup Iteration   3: 6.316 ops/ms
Iteration   1: 6.384 ops/ms
Iteration   2: 6.608 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.509 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (6.384, 6.509, 6.608), stdev = 0.114
  CI (99.9%): [4.423, 8.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.515 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.006 ms/op
Iteration   1: 3.961 ±(99.9%) 0.003 ms/op
Iteration   2: 3.884 ±(99.9%) 0.003 ms/op
Iteration   3: 3.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.910 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.884, 3.910, 3.961), stdev = 0.044
  CI (99.9%): [3.111, 4.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.003 ms/op
Iteration   1: 3.661 ±(99.9%) 0.002 ms/op
Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
Iteration   3: 3.605 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.626 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.605, 3.626, 3.661), stdev = 0.031
  CI (99.9%): [3.066, 4.185] (assumes normal distribution)


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
# Warmup Iteration   1: 5.523 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.004 ms/op
Iteration   1: 3.794 ±(99.9%) 0.009 ms/op
Iteration   2: 3.728 ±(99.9%) 0.005 ms/op
Iteration   3: 3.741 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.754 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.728, 3.754, 3.794), stdev = 0.035
  CI (99.9%): [3.110, 4.398] (assumes normal distribution)


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
# Warmup Iteration   1: 7.848 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.140 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 4.956 ±(99.9%) 0.014 ms/op
Iteration   1: 4.943 ±(99.9%) 0.010 ms/op
Iteration   2: 4.957 ±(99.9%) 0.022 ms/op
Iteration   3: 4.858 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.919 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (4.858, 4.919, 4.957), stdev = 0.053
  CI (99.9%): [3.944, 5.894] (assumes normal distribution)


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
# Warmup Iteration   1: 5.565 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.010 ms/op
Iteration   1: 3.789 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.752 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  11.097 ms/op
                 createUser·p0.9999: 19.384 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.791 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  13.296 ms/op
                 createUser·p0.9999: 54.759 ms/op
                 createUser·p1.00:   55.181 ms/op

Iteration   3: 3.718 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  20.773 ms/op
                 createUser·p0.9999: 28.377 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254933
  mean =      3.766 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 247678 
    [ 5.000, 10.000) = 6890 
    [10.000, 15.000) = 165 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 101 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     45.096 ms/op
     p(99.9990) =     54.949 ms/op
     p(99.9999) =     55.181 ms/op
    p(100.0000) =     55.181 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.007 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  8.604 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.645 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.436 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.633 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  13.467 ms/op
                 existUser·p0.9999: 19.818 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268699
  mean =      3.574 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12318 
    [ 2.500,  5.000) = 251157 
    [ 5.000,  7.500) = 4457 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     12.014 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     22.714 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 5.535 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.009 ms/op
Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  11.584 ms/op
                 getUser·p0.9999: 22.876 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.783 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.834 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  11.680 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 252257
  mean =      3.803 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5452 
    [ 2.500,  5.000) = 239243 
    [ 5.000,  7.500) = 6806 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     10.395 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     24.345 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 7.494 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.322 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.085 ±(99.9%) 0.016 ms/op
Iteration   1: 4.965 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   7.226 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  16.809 ms/op
                 listUser·p0.9999: 31.399 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 4.869 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.851 ms/op
                 listUser·p0.999:  15.814 ms/op
                 listUser·p0.9999: 18.424 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.992 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.275 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  22.609 ms/op
                 listUser·p0.9999: 28.042 ms/op
                 listUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194325
  mean =      4.941 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 129215 
    [ 5.000,  7.500) = 58010 
    [ 7.500, 10.000) = 5900 
    [10.000, 12.500) = 559 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     16.619 ms/op
     p(99.9900) =     27.417 ms/op
     p(99.9990) =     31.925 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.119 ± 2.272  ops/ms
ClientGrpc.existUser                       thrpt       3   8.795 ± 0.436  ops/ms
ClientGrpc.getUser                         thrpt       3   8.306 ± 2.150  ops/ms
ClientGrpc.listUser                        thrpt       3   6.509 ± 2.087  ops/ms
ClientGrpc.createUser                       avgt       3   3.910 ± 0.799   ms/op
ClientGrpc.existUser                        avgt       3   3.626 ± 0.560   ms/op
ClientGrpc.getUser                          avgt       3   3.754 ± 0.644   ms/op
ClientGrpc.listUser                         avgt       3   4.919 ± 0.975   ms/op
ClientGrpc.createUser                     sample  254933   3.766 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.818           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.792           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.452           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          45.096           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          55.181           ms/op
ClientGrpc.existUser                      sample  268699   3.574 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.696           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.014           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.266           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  252257   3.803 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.611           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.395           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.496           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  194325   4.941 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.442           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.619           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.417           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.080           ms/op
