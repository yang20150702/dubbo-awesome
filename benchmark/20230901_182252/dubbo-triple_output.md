# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 6.149 ops/ms
# Warmup Iteration   3: 8.904 ops/ms
Iteration   1: 9.624 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.794 ±(99.9%) 3.081 ops/ms [Average]
  (min, avg, max) = (9.624, 9.794, 9.962), stdev = 0.169
  CI (99.9%): [6.713, 12.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 9.016 ops/ms
# Warmup Iteration   3: 9.512 ops/ms
Iteration   1: 9.982 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.119 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (9.982, 10.119, 10.300), stdev = 0.164
  CI (99.9%): [7.136, 13.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 9.687 ops/ms
Iteration   1: 9.503 ops/ms
Iteration   2: 9.985 ops/ms
Iteration   3: 10.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.855 ±(99.9%) 5.620 ops/ms [Average]
  (min, avg, max) = (9.503, 9.855, 10.076), stdev = 0.308
  CI (99.9%): [4.234, 15.475] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 8.323 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.369 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (8.344, 8.369, 8.398), stdev = 0.028
  CI (99.9%): [7.864, 8.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.068 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.007 ms/op
Iteration   1: 3.342 ±(99.9%) 0.007 ms/op
Iteration   2: 3.388 ±(99.9%) 0.005 ms/op
Iteration   3: 3.174 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.301 ±(99.9%) 2.054 ms/op [Average]
  (min, avg, max) = (3.174, 3.301, 3.388), stdev = 0.113
  CI (99.9%): [1.247, 5.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.004 ms/op
Iteration   1: 3.177 ±(99.9%) 0.008 ms/op
Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.129 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.072, 3.129, 3.177), stdev = 0.053
  CI (99.9%): [2.157, 4.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 7.575 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.005 ms/op
Iteration   1: 3.205 ±(99.9%) 0.006 ms/op
Iteration   2: 3.412 ±(99.9%) 0.006 ms/op
Iteration   3: 3.197 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 2.230 ms/op [Average]
  (min, avg, max) = (3.197, 3.271, 3.412), stdev = 0.122
  CI (99.9%): [1.042, 5.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.045 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.005 ms/op
Iteration   1: 3.790 ±(99.9%) 0.009 ms/op
Iteration   2: 3.777 ±(99.9%) 0.007 ms/op
Iteration   3: 3.739 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.769 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.739, 3.769, 3.790), stdev = 0.026
  CI (99.9%): [3.291, 4.246] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 7.319 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
Iteration   1: 3.325 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  18.435 ms/op
                 createUser·p0.9999: 23.323 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.733 ms/op
                 createUser·p0.999:  20.382 ms/op
                 createUser·p0.9999: 23.596 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  17.551 ms/op
                 createUser·p0.9999: 20.171 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289567
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20530 
    [ 2.500,  5.000) = 259728 
    [ 5.000,  7.500) = 7841 
    [ 7.500, 10.000) = 968 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     23.070 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 25.952 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   2: 3.098 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  12.360 ms/op
                 existUser·p0.9999: 27.121 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 20.400 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310221
  mean =      3.093 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15149 
    [ 2.500,  5.000) = 287901 
    [ 5.000,  7.500) = 5903 
    [ 7.500, 10.000) = 882 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.905 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.341 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.011 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.434 ms/op
                 getUser·p0.999:  18.099 ms/op
                 getUser·p0.9999: 21.067 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.260 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  16.515 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  10.993 ms/op
                 getUser·p0.9999: 27.512 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288791
  mean =      3.320 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16572 
    [ 2.500,  5.000) = 263328 
    [ 5.000,  7.500) = 7323 
    [ 7.500, 10.000) = 1069 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     16.664 ms/op
     p(99.9900) =     26.652 ms/op
     p(99.9990) =     27.933 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.835 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.015 ms/op
Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.323 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.888 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 16.397 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.836 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247548
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 53 
    [ 2.500,  3.750) = 134496 
    [ 3.750,  5.000) = 102470 
    [ 5.000,  6.250) = 4301 
    [ 6.250,  7.500) = 3639 
    [ 7.500,  8.750) = 1380 
    [ 8.750, 10.000) = 472 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 152 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 158 
    [15.000, 16.250) = 91 
    [16.250, 17.500) = 70 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     14.252 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.486 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.794 ± 3.081  ops/ms
ClientPb.existUser                       thrpt       3  10.119 ± 2.983  ops/ms
ClientPb.getUser                         thrpt       3   9.855 ± 5.620  ops/ms
ClientPb.listUser                        thrpt       3   8.369 ± 0.505  ops/ms
ClientPb.createUser                       avgt       3   3.301 ± 2.054   ms/op
ClientPb.existUser                        avgt       3   3.129 ± 0.972   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 2.230   ms/op
ClientPb.listUser                         avgt       3   3.769 ± 0.477   ms/op
ClientPb.createUser                     sample  289567   3.313 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.005           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.070           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.264           ms/op
ClientPb.existUser                      sample  310221   3.093 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.223           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  288791   3.320 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.021           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.664           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.652           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  247548   3.876 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.982           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.252           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.302           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.940           ms/op
