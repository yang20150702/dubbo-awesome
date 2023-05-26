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
# Warmup Iteration   1: 1.727 ops/ms
# Warmup Iteration   2: 4.297 ops/ms
# Warmup Iteration   3: 6.228 ops/ms
Iteration   1: 6.027 ops/ms
Iteration   2: 6.316 ops/ms
Iteration   3: 6.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.170 ±(99.9%) 2.631 ops/ms [Average]
  (min, avg, max) = (6.027, 6.170, 6.316), stdev = 0.144
  CI (99.9%): [3.539, 8.800] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ops/ms
# Warmup Iteration   2: 6.526 ops/ms
# Warmup Iteration   3: 6.914 ops/ms
Iteration   1: 7.042 ops/ms
Iteration   2: 6.842 ops/ms
Iteration   3: 7.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.997 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (6.842, 6.997, 7.108), stdev = 0.138
  CI (99.9%): [4.475, 9.519] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 5.757 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 6.453 ops/ms
Iteration   2: 6.677 ops/ms
Iteration   3: 6.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.579 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (6.453, 6.579, 6.677), stdev = 0.115
  CI (99.9%): [4.483, 8.675] (assumes normal distribution)


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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 4.504 ops/ms
# Warmup Iteration   3: 5.107 ops/ms
Iteration   1: 5.203 ops/ms
Iteration   2: 5.320 ops/ms
Iteration   3: 5.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.246 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (5.203, 5.246, 5.320), stdev = 0.064
  CI (99.9%): [4.071, 6.421] (assumes normal distribution)


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
# Warmup Iteration   1: 7.782 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.271 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.951 ±(99.9%) 0.007 ms/op
Iteration   1: 4.795 ±(99.9%) 0.016 ms/op
Iteration   2: 4.847 ±(99.9%) 0.003 ms/op
Iteration   3: 4.760 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.801 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (4.760, 4.801, 4.847), stdev = 0.044
  CI (99.9%): [4.002, 5.599] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.883 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.918 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.012 ms/op
Iteration   1: 4.518 ±(99.9%) 0.008 ms/op
Iteration   2: 4.554 ±(99.9%) 0.005 ms/op
Iteration   3: 4.623 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.565 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (4.518, 4.565, 4.623), stdev = 0.053
  CI (99.9%): [3.593, 5.537] (assumes normal distribution)


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
# Warmup Iteration   1: 8.129 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.204 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.070 ±(99.9%) 0.009 ms/op
Iteration   1: 5.045 ±(99.9%) 0.004 ms/op
Iteration   2: 4.816 ±(99.9%) 0.005 ms/op
Iteration   3: 4.839 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.900 ±(99.9%) 2.298 ms/op [Average]
  (min, avg, max) = (4.816, 4.900, 5.045), stdev = 0.126
  CI (99.9%): [2.602, 7.197] (assumes normal distribution)


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
# Warmup Iteration   1: 9.323 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.917 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 6.468 ±(99.9%) 0.015 ms/op
Iteration   1: 6.261 ±(99.9%) 0.013 ms/op
Iteration   2: 6.299 ±(99.9%) 0.030 ms/op
Iteration   3: 6.129 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.230 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (6.129, 6.230, 6.299), stdev = 0.089
  CI (99.9%): [4.608, 7.851] (assumes normal distribution)


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
# Warmup Iteration   1: 8.403 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.461 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.016 ms/op
Iteration   1: 4.901 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.693 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  13.135 ms/op
                 createUser·p0.9999: 17.151 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 4.779 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   9.103 ms/op
                 createUser·p0.999:  14.132 ms/op
                 createUser·p0.9999: 23.787 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 4.912 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  15.102 ms/op
                 createUser·p0.9999: 24.592 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 197505
  mean =      4.863 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2630 
    [ 2.500,  5.000) = 120276 
    [ 5.000,  7.500) = 68899 
    [ 7.500, 10.000) = 4515 
    [10.000, 12.500) = 794 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     14.901 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     25.004 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 7.268 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.961 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.630 ±(99.9%) 0.016 ms/op
Iteration   1: 4.645 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.619 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  14.640 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 4.690 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   4.456 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.963 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 30.164 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 4.591 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   4.383 ms/op
                 existUser·p0.90:   5.857 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   8.323 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 27.973 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 206745
  mean =      4.642 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3815 
    [ 2.500,  5.000) = 144243 
    [ 5.000,  7.500) = 52930 
    [ 7.500, 10.000) = 4683 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     28.148 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 8.098 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.260 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.021 ±(99.9%) 0.018 ms/op
Iteration   1: 4.949 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   7.283 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  15.254 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 4.836 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  13.623 ms/op
                 getUser·p0.9999: 18.033 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   3: 4.859 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   8.814 ms/op
                 getUser·p0.999:  15.075 ms/op
                 getUser·p0.9999: 23.246 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 196746
  mean =      4.881 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2922 
    [ 2.500,  5.000) = 122132 
    [ 5.000,  7.500) = 64877 
    [ 7.500, 10.000) = 5814 
    [10.000, 12.500) = 627 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     14.963 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.020 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 9.485 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 7.106 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.334 ±(99.9%) 0.029 ms/op
Iteration   1: 6.334 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  18.441 ms/op
                 listUser·p0.9999: 22.310 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 6.450 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  21.313 ms/op
                 listUser·p0.9999: 32.943 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   3: 6.355 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   12.845 ms/op
                 listUser·p0.999:  21.549 ms/op
                 listUser·p0.9999: 29.390 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 150525
  mean =      6.379 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 31454 
    [ 5.000,  7.500) = 86721 
    [ 7.500, 10.000) = 24854 
    [10.000, 12.500) = 5659 
    [12.500, 15.000) = 1297 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      5.923 ms/op
     p(90.0000) =      8.880 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     20.216 ms/op
     p(99.9900) =     29.389 ms/op
     p(99.9990) =     33.816 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.170 ± 2.631  ops/ms
ClientGrpc.existUser                       thrpt       3   6.997 ± 2.522  ops/ms
ClientGrpc.getUser                         thrpt       3   6.579 ± 2.096  ops/ms
ClientGrpc.listUser                        thrpt       3   5.246 ± 1.175  ops/ms
ClientGrpc.createUser                       avgt       3   4.801 ± 0.799   ms/op
ClientGrpc.existUser                        avgt       3   4.565 ± 0.972   ms/op
ClientGrpc.getUser                          avgt       3   4.900 ± 2.298   ms/op
ClientGrpc.listUser                         avgt       3   6.230 ± 1.622   ms/op
ClientGrpc.createUser                     sample  197505   4.863 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.161           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.775           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.093           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.901           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.052           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  206745   4.642 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.947           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.693           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.011           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.484           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.148           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.605           ms/op
ClientGrpc.getUser                        sample  196746   4.881 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.139           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.169           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.939           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.093           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.200           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  150525   6.379 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.591           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.880           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.730           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.216           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.389           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.882           ms/op
