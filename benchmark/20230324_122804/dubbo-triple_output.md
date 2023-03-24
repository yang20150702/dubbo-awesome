# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.139 ops/ms
# Warmup Iteration   2: 2.640 ops/ms
# Warmup Iteration   3: 5.727 ops/ms
Iteration   1: 6.050 ops/ms
Iteration   2: 6.280 ops/ms
Iteration   3: 6.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.259 ±(99.9%) 3.628 ops/ms [Average]
  (min, avg, max) = (6.050, 6.259, 6.446), stdev = 0.199
  CI (99.9%): [2.631, 9.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.517 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 6.538 ops/ms
Iteration   1: 6.795 ops/ms
Iteration   2: 6.694 ops/ms
Iteration   3: 6.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.676 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (6.539, 6.676, 6.795), stdev = 0.129
  CI (99.9%): [4.327, 9.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 5.067 ops/ms
# Warmup Iteration   3: 6.057 ops/ms
Iteration   1: 6.143 ops/ms
Iteration   2: 5.868 ops/ms
Iteration   3: 6.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.039 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (5.868, 6.039, 6.143), stdev = 0.149
  CI (99.9%): [3.319, 8.758] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.275 ops/ms
# Warmup Iteration   3: 4.722 ops/ms
Iteration   1: 5.356 ops/ms
Iteration   2: 5.539 ops/ms
Iteration   3: 5.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.426 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (5.356, 5.426, 5.539), stdev = 0.099
  CI (99.9%): [3.628, 7.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.420 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.305 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.474 ±(99.9%) 0.010 ms/op
Iteration   1: 5.280 ±(99.9%) 0.012 ms/op
Iteration   2: 5.407 ±(99.9%) 0.011 ms/op
Iteration   3: 5.900 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.529 ±(99.9%) 5.973 ms/op [Average]
  (min, avg, max) = (5.280, 5.529, 5.900), stdev = 0.327
  CI (99.9%): [≈ 0, 11.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.472 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.932 ±(99.9%) 0.012 ms/op
Iteration   1: 5.029 ±(99.9%) 0.012 ms/op
Iteration   2: 5.013 ±(99.9%) 0.013 ms/op
Iteration   3: 4.894 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.978 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (4.894, 4.978, 5.029), stdev = 0.074
  CI (99.9%): [3.631, 6.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.572 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.015 ms/op
Iteration   1: 5.187 ±(99.9%) 0.012 ms/op
Iteration   2: 5.073 ±(99.9%) 0.012 ms/op
Iteration   3: 5.029 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.096 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (5.029, 5.096, 5.187), stdev = 0.082
  CI (99.9%): [3.606, 6.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.392 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.742 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.082 ±(99.9%) 0.011 ms/op
Iteration   1: 6.415 ±(99.9%) 0.012 ms/op
Iteration   2: 6.120 ±(99.9%) 0.017 ms/op
Iteration   3: 6.035 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.190 ±(99.9%) 3.646 ms/op [Average]
  (min, avg, max) = (6.035, 6.190, 6.415), stdev = 0.200
  CI (99.9%): [2.544, 9.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.741 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.292 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.025 ms/op
Iteration   1: 5.319 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  20.075 ms/op
                 createUser·p0.9999: 25.100 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 5.267 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 25.426 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 5.299 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.091 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   11.174 ms/op
                 createUser·p0.999:  23.630 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181171
  mean =      5.295 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 91677 
    [ 5.000,  7.500) = 81476 
    [ 7.500, 10.000) = 5990 
    [10.000, 12.500) = 1442 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =     10.212 ms/op
     p(99.9000) =     21.162 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.389 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.139 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.778 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.100 ±(99.9%) 0.018 ms/op
Iteration   1: 5.190 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.812 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 27.722 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 5.197 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.347 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   10.287 ms/op
                 existUser·p0.999:  22.426 ms/op
                 existUser·p0.9999: 32.108 ms/op
                 existUser·p1.00:   32.768 ms/op

Iteration   3: 5.307 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.064 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   7.063 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   11.846 ms/op
                 existUser·p0.999:  27.320 ms/op
                 existUser·p0.9999: 31.130 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183500
  mean =      5.231 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 109892 
    [ 5.000,  7.500) = 61665 
    [ 7.500, 10.000) = 9342 
    [10.000, 12.500) = 1701 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     24.887 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     34.614 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.959 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.358 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.020 ms/op
Iteration   1: 5.383 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.939 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   10.535 ms/op
                 getUser·p0.999:  22.955 ms/op
                 getUser·p0.9999: 33.496 ms/op
                 getUser·p1.00:   38.601 ms/op

Iteration   2: 5.437 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.143 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  21.891 ms/op
                 getUser·p0.9999: 30.812 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 5.279 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.012 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  23.529 ms/op
                 getUser·p0.9999: 27.196 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178876
  mean =      5.366 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 85679 
    [ 5.000,  7.500) = 83149 
    [ 7.500, 10.000) = 7914 
    [10.000, 12.500) = 1314 
    [12.500, 15.000) = 421 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     22.385 ms/op
     p(99.9900) =     33.296 ms/op
     p(99.9990) =     38.394 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.210 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.513 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.874 ±(99.9%) 0.022 ms/op
Iteration   1: 5.840 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  24.781 ms/op
                 listUser·p0.9999: 31.200 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 5.982 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.025 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  25.213 ms/op
                 listUser·p0.9999: 28.955 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   3: 6.048 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  19.694 ms/op
                 listUser·p0.9999: 24.712 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161138
  mean =      5.955 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 16083 
    [ 5.000,  7.500) = 132569 
    [ 7.500, 10.000) = 9770 
    [10.000, 12.500) = 1770 
    [12.500, 15.000) = 414 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.200 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     23.757 ms/op
     p(99.9900) =     30.648 ms/op
     p(99.9990) =     31.592 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.259 ± 3.628  ops/ms
ClientPb.existUser                       thrpt       3   6.676 ± 2.349  ops/ms
ClientPb.getUser                         thrpt       3   6.039 ± 2.719  ops/ms
ClientPb.listUser                        thrpt       3   5.426 ± 1.798  ops/ms
ClientPb.createUser                       avgt       3   5.529 ± 5.973   ms/op
ClientPb.existUser                        avgt       3   4.978 ± 1.348   ms/op
ClientPb.getUser                          avgt       3   5.096 ± 1.490   ms/op
ClientPb.listUser                         avgt       3   6.190 ± 3.646   ms/op
ClientPb.createUser                     sample  181171   5.295 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.529           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.212           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  183500   5.231 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.742           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.913           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.887           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  178876   5.366 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.338           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.385           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.296           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.601           ms/op
ClientPb.listUser                       sample  161138   5.955 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.306           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.026           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.757           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.648           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.752           ms/op
