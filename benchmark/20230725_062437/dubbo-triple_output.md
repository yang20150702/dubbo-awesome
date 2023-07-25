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
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 4.249 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.987 ±(99.9%) 7.315 ops/ms [Average]
  (min, avg, max) = (7.526, 7.987, 8.258), stdev = 0.401
  CI (99.9%): [0.671, 15.302] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.262 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.524 ops/ms
Iteration   2: 8.677 ops/ms
Iteration   3: 8.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.556 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (8.468, 8.556, 8.677), stdev = 0.108
  CI (99.9%): [6.583, 10.529] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.418 ops/ms
# Warmup Iteration   2: 6.992 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.102 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (8.026, 8.102, 8.158), stdev = 0.068
  CI (99.9%): [6.856, 9.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.212 ops/ms
# Warmup Iteration   2: 6.148 ops/ms
# Warmup Iteration   3: 6.570 ops/ms
Iteration   1: 7.251 ops/ms
Iteration   2: 7.113 ops/ms
Iteration   3: 6.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.094 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (6.919, 7.094, 7.251), stdev = 0.167
  CI (99.9%): [4.054, 10.134] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.766 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.010 ms/op
Iteration   1: 4.007 ±(99.9%) 0.006 ms/op
Iteration   2: 3.846 ±(99.9%) 0.012 ms/op
Iteration   3: 3.947 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.933 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.846, 3.933, 4.007), stdev = 0.081
  CI (99.9%): [2.449, 5.418] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.378 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.004 ms/op
Iteration   1: 3.814 ±(99.9%) 0.008 ms/op
Iteration   2: 3.936 ±(99.9%) 0.008 ms/op
Iteration   3: 3.805 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.852 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (3.805, 3.852, 3.936), stdev = 0.073
  CI (99.9%): [2.517, 5.187] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.676 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.005 ms/op
Iteration   1: 4.046 ±(99.9%) 0.007 ms/op
Iteration   2: 4.044 ±(99.9%) 0.007 ms/op
Iteration   3: 4.015 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.035 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (4.015, 4.035, 4.046), stdev = 0.017
  CI (99.9%): [3.719, 4.352] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.362 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.976 ±(99.9%) 0.012 ms/op
Iteration   1: 4.867 ±(99.9%) 0.003 ms/op
Iteration   2: 4.632 ±(99.9%) 0.015 ms/op
Iteration   3: 4.728 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.742 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (4.632, 4.742, 4.867), stdev = 0.118
  CI (99.9%): [2.591, 6.893] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.234 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.918 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.471 ±(99.9%) 0.019 ms/op
Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  13.529 ms/op
                 createUser·p0.9999: 24.316 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  22.853 ms/op
                 createUser·p0.9999: 25.291 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  25.686 ms/op
                 createUser·p0.9999: 35.376 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242309
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 241 
    [ 2.500,  5.000) = 231634 
    [ 5.000,  7.500) = 8664 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     22.043 ms/op
     p(99.9900) =     33.423 ms/op
     p(99.9990) =     35.531 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.478 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 3.634 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  22.672 ms/op
                 existUser·p0.9999: 25.074 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.679 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 27.208 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.736 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  24.601 ms/op
                 existUser·p0.9999: 34.435 ms/op
                 existUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 260617
  mean =      3.682 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 254736 
    [ 5.000, 10.000) = 5433 
    [10.000, 15.000) = 161 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 115 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     33.292 ms/op
     p(99.9990) =     35.812 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.014 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.530 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.015 ms/op
Iteration   1: 3.882 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  22.335 ms/op
                 getUser·p0.9999: 30.048 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  23.913 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.888 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  12.071 ms/op
                 getUser·p0.9999: 28.934 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247886
  mean =      3.871 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 240861 
    [ 5.000,  7.500) = 5410 
    [ 7.500, 10.000) = 945 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     21.574 ms/op
     p(99.9900) =     29.007 ms/op
     p(99.9990) =     30.721 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.137 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.618 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.703 ±(99.9%) 0.016 ms/op
Iteration   1: 4.734 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   9.185 ms/op
                 listUser·p0.999:  24.132 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.599 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  16.554 ms/op
                 listUser·p0.9999: 24.185 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.654 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.097 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 27.084 ms/op
                 listUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205792
  mean =      4.662 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 180396 
    [ 5.000,  7.500) = 20994 
    [ 7.500, 10.000) = 3325 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.987 ± 7.315  ops/ms
ClientPb.existUser                       thrpt       3   8.556 ± 1.973  ops/ms
ClientPb.getUser                         thrpt       3   8.102 ± 1.245  ops/ms
ClientPb.listUser                        thrpt       3   7.094 ± 3.040  ops/ms
ClientPb.createUser                       avgt       3   3.933 ± 1.485   ms/op
ClientPb.existUser                        avgt       3   3.852 ± 1.335   ms/op
ClientPb.getUser                          avgt       3   4.035 ± 0.317   ms/op
ClientPb.listUser                         avgt       3   4.742 ± 2.151   ms/op
ClientPb.createUser                     sample  242309   3.965 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.194           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.043           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.423           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  260617   3.682 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.225           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.385           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.292           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.305           ms/op
ClientPb.getUser                        sample  247886   3.871 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.413           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.758           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.574           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  205792   4.662 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.360           ms/op
