# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
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
# Warmup Iteration   2: 6.419 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 9.733 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.888 ±(99.9%) 3.090 ops/ms [Average]
  (min, avg, max) = (9.733, 9.888, 10.069), stdev = 0.169
  CI (99.9%): [6.798, 12.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 9.948 ops/ms
Iteration   1: 9.909 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.171 ±(99.9%) 4.205 ops/ms [Average]
  (min, avg, max) = (9.909, 10.171, 10.342), stdev = 0.230
  CI (99.9%): [5.966, 14.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 9.126 ops/ms
# Warmup Iteration   3: 9.690 ops/ms
Iteration   1: 10.107 ops/ms
Iteration   2: 9.790 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.860 ±(99.9%) 4.025 ops/ms [Average]
  (min, avg, max) = (9.682, 9.860, 10.107), stdev = 0.221
  CI (99.9%): [5.834, 13.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.539 ops/ms
Iteration   3: 8.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.513 ±(99.9%) 0.753 ops/ms [Average]
  (min, avg, max) = (8.465, 8.513, 8.539), stdev = 0.041
  CI (99.9%): [7.760, 9.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.002 ms/op
Iteration   1: 3.302 ±(99.9%) 0.006 ms/op
Iteration   2: 3.262 ±(99.9%) 0.005 ms/op
Iteration   3: 3.195 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.253 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.195, 3.253, 3.302), stdev = 0.054
  CI (99.9%): [2.271, 4.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.223 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
Iteration   3: 3.024 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.043 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.024, 3.043, 3.073), stdev = 0.026
  CI (99.9%): [2.565, 3.521] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.004 ms/op
Iteration   1: 3.142 ±(99.9%) 0.007 ms/op
Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.121 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.086, 3.121, 3.142), stdev = 0.031
  CI (99.9%): [2.561, 3.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.939 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.008 ms/op
Iteration   1: 3.730 ±(99.9%) 0.008 ms/op
Iteration   2: 3.773 ±(99.9%) 0.009 ms/op
Iteration   3: 3.795 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.766 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.730, 3.766, 3.795), stdev = 0.033
  CI (99.9%): [3.157, 4.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.031 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  17.524 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.494 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 22.542 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.185 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305536
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19241 
    [ 2.500,  5.000) = 282145 
    [ 5.000,  7.500) = 3352 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.338 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     28.370 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.446 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.009 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 22.788 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  12.903 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 22.975 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310550
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24225 
    [ 2.500,  5.000) = 281773 
    [ 5.000,  7.500) = 3808 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     26.783 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.545 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.010 ms/op
Iteration   1: 3.287 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  16.099 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.658 ms/op

Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 22.956 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  10.143 ms/op
                 getUser·p0.9999: 20.568 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302182
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8420 
    [ 2.500,  5.000) = 288485 
    [ 5.000,  7.500) = 4327 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.011 ms/op
     p(99.9900) =     22.603 ms/op
     p(99.9990) =     23.657 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.188 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 22.075 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.495 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  13.778 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246196
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 233879 
    [ 5.000,  7.500) = 10147 
    [ 7.500, 10.000) = 1470 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.888 ± 3.090  ops/ms
ClientPb.existUser                       thrpt       3  10.171 ± 4.205  ops/ms
ClientPb.getUser                         thrpt       3   9.860 ± 4.025  ops/ms
ClientPb.listUser                        thrpt       3   8.513 ± 0.753  ops/ms
ClientPb.createUser                       avgt       3   3.253 ± 0.982   ms/op
ClientPb.existUser                        avgt       3   3.043 ± 0.478   ms/op
ClientPb.getUser                          avgt       3   3.121 ± 0.560   ms/op
ClientPb.listUser                         avgt       3   3.766 ± 0.609   ms/op
ClientPb.createUser                     sample  305536   3.140 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.684           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.338           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.117           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  310550   3.090 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.756           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  302182   3.176 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.011           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.603           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  246196   3.896 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.840           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.544           ms/op
