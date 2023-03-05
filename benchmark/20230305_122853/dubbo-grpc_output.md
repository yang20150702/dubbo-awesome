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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.478 ops/ms
# Warmup Iteration   3: 7.676 ops/ms
Iteration   1: 7.415 ops/ms
Iteration   2: 7.452 ops/ms
Iteration   3: 7.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.460 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (7.415, 7.460, 7.513), stdev = 0.049
  CI (99.9%): [6.558, 8.363] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.014 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.137 ops/ms
Iteration   2: 7.814 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.149 ±(99.9%) 6.231 ops/ms [Average]
  (min, avg, max) = (7.814, 8.149, 8.496), stdev = 0.342
  CI (99.9%): [1.918, 14.380] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ops/ms
# Warmup Iteration   2: 7.239 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.967 ±(99.9%) 3.953 ops/ms [Average]
  (min, avg, max) = (7.806, 7.967, 8.213), stdev = 0.217
  CI (99.9%): [4.014, 11.920] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.715 ops/ms
# Warmup Iteration   2: 6.038 ops/ms
# Warmup Iteration   3: 6.278 ops/ms
Iteration   1: 6.558 ops/ms
Iteration   2: 6.390 ops/ms
Iteration   3: 6.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.344 ±(99.9%) 4.404 ops/ms [Average]
  (min, avg, max) = (6.082, 6.344, 6.558), stdev = 0.241
  CI (99.9%): [1.940, 10.748] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.302 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.012 ms/op
Iteration   1: 4.236 ±(99.9%) 0.002 ms/op
Iteration   2: 4.164 ±(99.9%) 0.003 ms/op
Iteration   3: 4.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.180 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (4.142, 4.180, 4.236), stdev = 0.049
  CI (99.9%): [3.282, 5.078] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.644 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.005 ms/op
Iteration   1: 3.901 ±(99.9%) 0.003 ms/op
Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
Iteration   3: 3.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.858 ±(99.9%) 2.200 ms/op [Average]
  (min, avg, max) = (3.722, 3.858, 3.952), stdev = 0.121
  CI (99.9%): [1.659, 6.058] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.007 ms/op
Iteration   1: 4.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.961 ±(99.9%) 0.003 ms/op
Iteration   3: 4.127 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.051 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.961, 4.051, 4.127), stdev = 0.084
  CI (99.9%): [2.522, 5.580] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.556 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.381 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.217 ±(99.9%) 0.032 ms/op
Iteration   1: 5.051 ±(99.9%) 0.015 ms/op
Iteration   2: 4.925 ±(99.9%) 0.011 ms/op
Iteration   3: 4.831 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.935 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (4.831, 4.935, 5.051), stdev = 0.110
  CI (99.9%): [2.921, 6.949] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.929 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.013 ms/op
Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  9.105 ms/op
                 createUser·p0.9999: 18.511 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  13.087 ms/op
                 createUser·p0.9999: 23.333 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   5.063 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  11.686 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 243329
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7607 
    [ 2.500,  5.000) = 209574 
    [ 5.000,  7.500) = 24844 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     11.463 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     24.013 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
Iteration   1: 4.090 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  12.126 ms/op
                 existUser·p0.9999: 15.191 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   5.079 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 18.515 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 3.979 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   5.120 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  11.299 ms/op
                 existUser·p0.9999: 21.396 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238296
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9190 
    [ 2.500,  5.000) = 198741 
    [ 5.000,  7.500) = 28082 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     11.644 ms/op
     p(99.9900) =     19.390 ms/op
     p(99.9990) =     21.720 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 6.253 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.012 ms/op
Iteration   1: 4.227 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   8.126 ms/op
                 getUser·p0.999:  11.687 ms/op
                 getUser·p0.9999: 16.026 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 21.591 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   3: 4.216 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  14.008 ms/op
                 getUser·p0.9999: 22.066 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227154
  mean =      4.227 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5886 
    [ 2.500,  5.000) = 182101 
    [ 5.000,  7.500) = 36664 
    [ 7.500, 10.000) = 1991 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     20.770 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.998 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.635 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.201 ±(99.9%) 0.017 ms/op
Iteration   1: 5.020 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  15.837 ms/op
                 listUser·p0.9999: 23.646 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 5.040 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  16.694 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 5.091 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  18.429 ms/op
                 listUser·p0.9999: 29.819 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 190049
  mean =      5.050 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174 
    [ 2.500,  5.000) = 110188 
    [ 5.000,  7.500) = 72296 
    [ 7.500, 10.000) = 6235 
    [10.000, 12.500) = 691 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     17.136 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     29.973 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.460 ± 0.903  ops/ms
ClientGrpc.existUser                       thrpt       3   8.149 ± 6.231  ops/ms
ClientGrpc.getUser                         thrpt       3   7.967 ± 3.953  ops/ms
ClientGrpc.listUser                        thrpt       3   6.344 ± 4.404  ops/ms
ClientGrpc.createUser                       avgt       3   4.180 ± 0.898   ms/op
ClientGrpc.existUser                        avgt       3   3.858 ± 2.200   ms/op
ClientGrpc.getUser                          avgt       3   4.051 ± 1.529   ms/op
ClientGrpc.listUser                         avgt       3   4.935 ± 2.014   ms/op
ClientGrpc.createUser                     sample  243329   3.947 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.578           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.463           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.265           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.642           ms/op
ClientGrpc.existUser                      sample  238296   4.028 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.885           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.153           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.390           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  227154   4.227 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.709           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.271           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.770           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  190049   5.050 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.186           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.208           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.136           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.179           ms/op
