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
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 5.377 ops/ms
# Warmup Iteration   3: 7.236 ops/ms
Iteration   1: 7.621 ops/ms
Iteration   2: 7.681 ops/ms
Iteration   3: 7.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.676 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (7.621, 7.676, 7.725), stdev = 0.053
  CI (99.9%): [6.716, 8.635] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 8.531 ops/ms
Iteration   2: 8.602 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.526 ±(99.9%) 1.428 ops/ms [Average]
  (min, avg, max) = (8.446, 8.526, 8.602), stdev = 0.078
  CI (99.9%): [7.098, 9.955] (assumes normal distribution)


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
# Warmup Iteration   1: 4.775 ops/ms
# Warmup Iteration   2: 7.171 ops/ms
# Warmup Iteration   3: 7.771 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.183 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (8.060, 8.183, 8.313), stdev = 0.126
  CI (99.9%): [5.875, 10.490] (assumes normal distribution)


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
# Warmup Iteration   1: 3.759 ops/ms
# Warmup Iteration   2: 5.573 ops/ms
# Warmup Iteration   3: 5.888 ops/ms
Iteration   1: 6.096 ops/ms
Iteration   2: 6.154 ops/ms
Iteration   3: 6.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.157 ±(99.9%) 1.145 ops/ms [Average]
  (min, avg, max) = (6.096, 6.157, 6.221), stdev = 0.063
  CI (99.9%): [5.012, 7.302] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.337 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.005 ms/op
Iteration   1: 4.069 ±(99.9%) 0.003 ms/op
Iteration   2: 4.099 ±(99.9%) 0.004 ms/op
Iteration   3: 4.066 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.078 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (4.066, 4.078, 4.099), stdev = 0.018
  CI (99.9%): [3.747, 4.410] (assumes normal distribution)


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
# Warmup Iteration   1: 5.783 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.800 ±(99.9%) 0.003 ms/op
Iteration   2: 3.745 ±(99.9%) 0.002 ms/op
Iteration   3: 3.765 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.770 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.745, 3.770, 3.800), stdev = 0.028
  CI (99.9%): [3.264, 4.276] (assumes normal distribution)


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
# Warmup Iteration   1: 6.396 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.919 ±(99.9%) 0.003 ms/op
Iteration   2: 3.937 ±(99.9%) 0.003 ms/op
Iteration   3: 4.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.957 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.919, 3.957, 4.015), stdev = 0.051
  CI (99.9%): [3.032, 4.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.405 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.015 ms/op
Iteration   1: 5.323 ±(99.9%) 0.024 ms/op
Iteration   2: 5.280 ±(99.9%) 0.012 ms/op
Iteration   3: 5.339 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.314 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (5.280, 5.314, 5.339), stdev = 0.031
  CI (99.9%): [4.755, 5.872] (assumes normal distribution)


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
# Warmup Iteration   1: 6.598 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.013 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.355 ms/op
                 createUser·p0.999:  15.856 ms/op
                 createUser·p0.9999: 19.331 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 4.067 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  13.227 ms/op
                 createUser·p0.9999: 17.764 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   3: 4.037 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 19.316 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 238213
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8216 
    [ 2.500,  5.000) = 203212 
    [ 5.000,  7.500) = 24624 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     19.077 ms/op
     p(99.9990) =     20.475 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 5.626 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.009 ms/op
Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.769 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  9.761 ms/op
                 existUser·p0.9999: 17.226 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 3.827 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.699 ms/op
                 existUser·p0.999:  14.735 ms/op
                 existUser·p0.9999: 19.604 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   3: 3.672 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  11.597 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253963
  mean =      3.778 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8744 
    [ 2.500,  5.000) = 229865 
    [ 5.000,  7.500) = 13939 
    [ 7.500, 10.000) = 1015 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     31.300 ms/op
     p(99.9990) =     32.143 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.348 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.012 ms/op
Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  12.297 ms/op
                 getUser·p0.9999: 16.123 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   2: 4.149 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  11.597 ms/op
                 getUser·p0.9999: 19.867 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   3: 4.138 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.679 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 22.225 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233613
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6605 
    [ 2.500,  5.000) = 198021 
    [ 5.000,  7.500) = 26626 
    [ 7.500, 10.000) = 1762 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.468 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.451 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.892 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.417 ±(99.9%) 0.021 ms/op
Iteration   1: 5.320 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.098 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  17.232 ms/op
                 listUser·p0.9999: 20.477 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 5.313 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 20.181 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 5.341 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  20.158 ms/op
                 listUser·p0.9999: 24.248 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180141
  mean =      5.325 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170 
    [ 2.500,  5.000) = 88119 
    [ 5.000,  7.500) = 78918 
    [ 7.500, 10.000) = 10456 
    [10.000, 12.500) = 1861 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.837 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.676 ± 0.960  ops/ms
ClientGrpc.existUser                       thrpt       3   8.526 ± 1.428  ops/ms
ClientGrpc.getUser                         thrpt       3   8.183 ± 2.308  ops/ms
ClientGrpc.listUser                        thrpt       3   6.157 ± 1.145  ops/ms
ClientGrpc.createUser                       avgt       3   4.078 ± 0.331   ms/op
ClientGrpc.existUser                        avgt       3   3.770 ± 0.506   ms/op
ClientGrpc.getUser                          avgt       3   3.957 ± 0.925   ms/op
ClientGrpc.listUser                         avgt       3   5.314 ± 0.559   ms/op
ClientGrpc.createUser                     sample  238213   4.028 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.563           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.587           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.332           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.077           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  253963   3.778 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.661           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.091           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.211           ms/op
ClientGrpc.getUser                        sample  233613   4.108 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.791           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.577           ms/op
ClientGrpc.listUser                       sample  180141   5.325 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.953           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.469           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.547           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
