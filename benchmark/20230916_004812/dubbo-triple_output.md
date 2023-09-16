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
# Warmup Iteration   1: 2.127 ops/ms
# Warmup Iteration   2: 5.364 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.094 ±(99.9%) 2.338 ops/ms [Average]
  (min, avg, max) = (8.988, 9.094, 9.237), stdev = 0.128
  CI (99.9%): [6.757, 11.432] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.763 ops/ms
# Warmup Iteration   2: 8.444 ops/ms
# Warmup Iteration   3: 9.528 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.879 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.713 ±(99.9%) 2.641 ops/ms [Average]
  (min, avg, max) = (9.614, 9.713, 9.879), stdev = 0.145
  CI (99.9%): [7.072, 12.354] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 9.213 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.234 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (9.159, 9.234, 9.293), stdev = 0.068
  CI (99.9%): [7.984, 10.483] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.767 ops/ms
# Warmup Iteration   2: 7.228 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 7.892 ops/ms
Iteration   3: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.804 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (7.630, 7.804, 7.892), stdev = 0.151
  CI (99.9%): [5.057, 10.551] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.256 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.005 ms/op
Iteration   1: 3.588 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.003 ms/op
Iteration   3: 3.456 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.456, 3.503, 3.588), stdev = 0.074
  CI (99.9%): [2.156, 4.850] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.428 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.004 ms/op
Iteration   1: 3.375 ±(99.9%) 0.003 ms/op
Iteration   2: 3.332 ±(99.9%) 0.004 ms/op
Iteration   3: 3.359 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.355 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (3.332, 3.355, 3.375), stdev = 0.022
  CI (99.9%): [2.961, 3.750] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.582 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.004 ms/op
Iteration   1: 3.471 ±(99.9%) 0.004 ms/op
Iteration   2: 3.527 ±(99.9%) 0.006 ms/op
Iteration   3: 3.524 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.507 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.471, 3.507, 3.527), stdev = 0.031
  CI (99.9%): [2.933, 4.081] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.012 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.006 ms/op
Iteration   1: 4.137 ±(99.9%) 0.006 ms/op
Iteration   2: 4.193 ±(99.9%) 0.007 ms/op
Iteration   3: 4.126 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.152 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (4.126, 4.152, 4.193), stdev = 0.036
  CI (99.9%): [3.501, 4.803] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.627 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.479 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  20.565 ms/op
                 createUser·p0.9999: 24.047 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.472 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  14.314 ms/op
                 createUser·p0.9999: 27.116 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.479 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  12.943 ms/op
                 createUser·p0.9999: 61.080 ms/op
                 createUser·p1.00:   62.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275731
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270526 
    [ 5.000, 10.000) = 4718 
    [10.000, 15.000) = 221 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 138 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.509 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     62.176 ms/op
     p(99.9999) =     62.456 ms/op
    p(100.0000) =     62.456 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.991 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.007 ms/op
Iteration   1: 3.335 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  21.671 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.475 ms/op
                 existUser·p0.999:  24.119 ms/op
                 existUser·p0.9999: 27.610 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   3: 3.410 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  14.460 ms/op
                 existUser·p0.9999: 30.724 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283557
  mean =      3.383 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5573 
    [ 2.500,  5.000) = 272302 
    [ 5.000,  7.500) = 4094 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     31.627 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.012 ms/op
Iteration   1: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  22.749 ms/op
                 getUser·p0.9999: 26.013 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 3.529 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  22.656 ms/op
                 getUser·p0.9999: 26.866 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  21.102 ms/op
                 getUser·p0.9999: 28.669 ms/op
                 getUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271843
  mean =      3.527 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3958 
    [ 2.500,  5.000) = 261102 
    [ 5.000,  7.500) = 5499 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     27.585 ms/op
     p(99.9990) =     29.576 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.013 ms/op
Iteration   1: 4.355 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  22.891 ms/op
                 listUser·p0.9999: 29.993 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   2: 4.055 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.533 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 19.042 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   3: 4.160 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 18.997 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229154
  mean =      4.186 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 218661 
    [ 5.000,  7.500) = 8525 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     16.070 ms/op
     p(99.9900) =     26.613 ms/op
     p(99.9990) =     30.170 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.094 ± 2.338  ops/ms
ClientPb.existUser                       thrpt       3   9.713 ± 2.641  ops/ms
ClientPb.getUser                         thrpt       3   9.234 ± 1.249  ops/ms
ClientPb.listUser                        thrpt       3   7.804 ± 2.747  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 1.347   ms/op
ClientPb.existUser                        avgt       3   3.355 ± 0.395   ms/op
ClientPb.getUser                          avgt       3   3.507 ± 0.574   ms/op
ClientPb.listUser                         avgt       3   4.152 ± 0.651   ms/op
ClientPb.createUser                     sample  275731   3.476 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.534           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.509           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.165           ms/op
ClientPb.createUser:createUser·p1.00    sample          62.456           ms/op
ClientPb.existUser                      sample  283557   3.383 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  271843   3.527 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.463           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.585           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  229154   4.186 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.673           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.070           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.613           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.212           ms/op
