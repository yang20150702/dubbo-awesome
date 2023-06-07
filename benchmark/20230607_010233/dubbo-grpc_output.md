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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.865 ops/ms
# Warmup Iteration   3: 7.255 ops/ms
Iteration   1: 7.865 ops/ms
Iteration   2: 8.030 ops/ms
Iteration   3: 7.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.865 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (7.700, 7.865, 8.030), stdev = 0.165
  CI (99.9%): [4.850, 10.880] (assumes normal distribution)


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
# Warmup Iteration   1: 5.557 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 8.508 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.535 ±(99.9%) 2.773 ops/ms [Average]
  (min, avg, max) = (8.398, 8.535, 8.698), stdev = 0.152
  CI (99.9%): [5.762, 11.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ops/ms
# Warmup Iteration   2: 7.119 ops/ms
# Warmup Iteration   3: 7.666 ops/ms
Iteration   1: 7.786 ops/ms
Iteration   2: 7.877 ops/ms
Iteration   3: 7.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.870 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (7.786, 7.870, 7.947), stdev = 0.081
  CI (99.9%): [6.393, 9.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ops/ms
# Warmup Iteration   2: 5.851 ops/ms
# Warmup Iteration   3: 6.252 ops/ms
Iteration   1: 6.275 ops/ms
Iteration   2: 6.229 ops/ms
Iteration   3: 6.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.202 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (6.102, 6.202, 6.275), stdev = 0.090
  CI (99.9%): [4.568, 7.837] (assumes normal distribution)


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
# Warmup Iteration   1: 5.800 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.007 ms/op
Iteration   1: 3.883 ±(99.9%) 0.003 ms/op
Iteration   2: 3.964 ±(99.9%) 0.003 ms/op
Iteration   3: 3.898 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.915 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.883, 3.915, 3.964), stdev = 0.043
  CI (99.9%): [3.127, 4.703] (assumes normal distribution)


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
# Warmup Iteration   1: 5.335 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.003 ms/op
Iteration   1: 3.765 ±(99.9%) 0.004 ms/op
Iteration   2: 3.880 ±(99.9%) 0.004 ms/op
Iteration   3: 3.650 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.765 ±(99.9%) 2.102 ms/op [Average]
  (min, avg, max) = (3.650, 3.765, 3.880), stdev = 0.115
  CI (99.9%): [1.663, 5.867] (assumes normal distribution)


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
# Warmup Iteration   1: 5.573 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.004 ms/op
Iteration   1: 4.111 ±(99.9%) 0.004 ms/op
Iteration   2: 4.029 ±(99.9%) 0.003 ms/op
Iteration   3: 3.932 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.024 ±(99.9%) 1.634 ms/op [Average]
  (min, avg, max) = (3.932, 4.024, 4.111), stdev = 0.090
  CI (99.9%): [2.390, 5.658] (assumes normal distribution)


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
# Warmup Iteration   1: 7.624 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.690 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.977 ±(99.9%) 0.013 ms/op
Iteration   1: 4.889 ±(99.9%) 0.012 ms/op
Iteration   2: 4.857 ±(99.9%) 0.015 ms/op
Iteration   3: 5.041 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.929 ±(99.9%) 1.792 ms/op [Average]
  (min, avg, max) = (4.857, 4.929, 5.041), stdev = 0.098
  CI (99.9%): [3.137, 6.721] (assumes normal distribution)


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
# Warmup Iteration   1: 6.248 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
Iteration   1: 4.005 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  13.271 ms/op
                 createUser·p0.9999: 29.066 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   2: 3.732 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 19.630 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.686 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  9.515 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252456
  mean =      3.803 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4887 
    [ 2.500,  5.000) = 228319 
    [ 5.000,  7.500) = 18247 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.881 ms/op
     p(99.9900) =     28.124 ms/op
     p(99.9990) =     29.504 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 5.205 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  8.878 ms/op
                 existUser·p0.9999: 14.659 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 3.587 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  10.021 ms/op
                 existUser·p0.9999: 16.141 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.548 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272558
  mean =      3.522 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 7849 
    [ 2.500,  3.750) = 181738 
    [ 3.750,  5.000) = 73544 
    [ 5.000,  6.250) = 7099 
    [ 6.250,  7.500) = 1382 
    [ 7.500,  8.750) = 356 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =      9.428 ms/op
     p(99.9900) =     17.588 ms/op
     p(99.9990) =     18.031 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.924 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.011 ms/op
Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 13.583 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.556 ms/op
                 getUser·p0.999:  11.758 ms/op
                 getUser·p0.9999: 20.403 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 20.341 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248445
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9854 
    [ 2.500,  5.000) = 218839 
    [ 5.000,  7.500) = 18500 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.445 ms/op
     p(99.9900) =     20.163 ms/op
     p(99.9990) =     20.743 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 8.119 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.449 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.018 ms/op
Iteration   1: 5.377 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.155 ms/op
                 listUser·p0.999:  21.373 ms/op
                 listUser·p0.9999: 37.446 ms/op
                 listUser·p1.00:   38.863 ms/op

Iteration   2: 5.230 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.511 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 22.540 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 5.159 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   9.792 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 33.253 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182791
  mean =      5.254 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 94774 
    [ 5.000,  7.500) = 75191 
    [ 7.500, 10.000) = 10556 
    [10.000, 12.500) = 1335 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     38.375 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.865 ± 3.015  ops/ms
ClientGrpc.existUser                       thrpt       3   8.535 ± 2.773  ops/ms
ClientGrpc.getUser                         thrpt       3   7.870 ± 1.476  ops/ms
ClientGrpc.listUser                        thrpt       3   6.202 ± 1.635  ops/ms
ClientGrpc.createUser                       avgt       3   3.915 ± 0.788   ms/op
ClientGrpc.existUser                        avgt       3   3.765 ± 2.102   ms/op
ClientGrpc.getUser                          avgt       3   4.024 ± 1.634   ms/op
ClientGrpc.listUser                         avgt       3   4.929 ± 1.792   ms/op
ClientGrpc.createUser                     sample  252456   3.803 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.873           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.504           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.881           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.124           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.655           ms/op
ClientGrpc.existUser                      sample  272558   3.522 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.428           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.588           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  248445   3.862 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.794           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.445           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.163           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  182791   5.254 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.864           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.857           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.914           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.863           ms/op
