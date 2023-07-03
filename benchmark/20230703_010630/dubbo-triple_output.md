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
# Warmup Iteration   1: 0.921 ops/ms
# Warmup Iteration   2: 2.050 ops/ms
# Warmup Iteration   3: 4.568 ops/ms
Iteration   1: 5.222 ops/ms
Iteration   2: 5.726 ops/ms
Iteration   3: 5.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.622 ±(99.9%) 6.569 ops/ms [Average]
  (min, avg, max) = (5.222, 5.622, 5.919), stdev = 0.360
  CI (99.9%): [≈ 0, 12.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.548 ops/ms
# Warmup Iteration   2: 4.716 ops/ms
# Warmup Iteration   3: 5.952 ops/ms
Iteration   1: 5.992 ops/ms
Iteration   2: 6.085 ops/ms
Iteration   3: 5.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.001 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (5.927, 6.001, 6.085), stdev = 0.079
  CI (99.9%): [4.561, 7.442] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.747 ops/ms
# Warmup Iteration   2: 4.352 ops/ms
# Warmup Iteration   3: 5.784 ops/ms
Iteration   1: 5.588 ops/ms
Iteration   2: 5.723 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.739 ±(99.9%) 2.919 ops/ms [Average]
  (min, avg, max) = (5.588, 5.739, 5.907), stdev = 0.160
  CI (99.9%): [2.821, 8.658] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.463 ops/ms
# Warmup Iteration   2: 4.072 ops/ms
# Warmup Iteration   3: 5.040 ops/ms
Iteration   1: 4.864 ops/ms
Iteration   2: 5.089 ops/ms
Iteration   3: 5.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.131 ±(99.9%) 5.302 ops/ms [Average]
  (min, avg, max) = (4.864, 5.131, 5.441), stdev = 0.291
  CI (99.9%): [≈ 0, 10.433] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.923 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.547 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.971 ±(99.9%) 0.009 ms/op
Iteration   1: 5.619 ±(99.9%) 0.013 ms/op
Iteration   2: 5.779 ±(99.9%) 0.010 ms/op
Iteration   3: 5.558 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.652 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (5.558, 5.652, 5.779), stdev = 0.114
  CI (99.9%): [3.569, 7.735] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.581 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.014 ms/op
Iteration   1: 5.142 ±(99.9%) 0.011 ms/op
Iteration   2: 5.075 ±(99.9%) 0.016 ms/op
Iteration   3: 4.813 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.010 ±(99.9%) 3.172 ms/op [Average]
  (min, avg, max) = (4.813, 5.010, 5.142), stdev = 0.174
  CI (99.9%): [1.837, 8.182] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.959 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.829 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.323 ±(99.9%) 0.008 ms/op
Iteration   1: 5.235 ±(99.9%) 0.009 ms/op
Iteration   2: 5.295 ±(99.9%) 0.017 ms/op
Iteration   3: 4.992 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.174 ±(99.9%) 2.925 ms/op [Average]
  (min, avg, max) = (4.992, 5.174, 5.295), stdev = 0.160
  CI (99.9%): [2.249, 8.100] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.315 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.357 ±(99.9%) 0.012 ms/op
Iteration   1: 6.156 ±(99.9%) 0.015 ms/op
Iteration   2: 6.207 ±(99.9%) 0.018 ms/op
Iteration   3: 6.223 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.195 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (6.156, 6.195, 6.223), stdev = 0.035
  CI (99.9%): [5.559, 6.831] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.518 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.055 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.108 ±(99.9%) 0.027 ms/op
Iteration   1: 5.935 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   12.237 ms/op
                 createUser·p0.999:  23.209 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   2: 6.032 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.710 ms/op
                 createUser·p0.90:   7.741 ms/op
                 createUser·p0.95:   8.521 ms/op
                 createUser·p0.99:   11.217 ms/op
                 createUser·p0.999:  16.063 ms/op
                 createUser·p0.9999: 29.838 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 5.664 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   7.078 ms/op
                 createUser·p0.95:   7.905 ms/op
                 createUser·p0.99:   10.322 ms/op
                 createUser·p0.999:  21.823 ms/op
                 createUser·p0.9999: 29.339 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163299
  mean =      5.873 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 40969 
    [ 5.000,  7.500) = 105866 
    [ 7.500, 10.000) = 13281 
    [10.000, 12.500) = 2159 
    [12.500, 15.000) = 458 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     29.317 ms/op
     p(99.9990) =     30.414 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.601 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.162 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.396 ±(99.9%) 0.018 ms/op
Iteration   1: 5.338 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   10.895 ms/op
                 existUser·p0.999:  14.505 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 5.524 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  24.558 ms/op
                 existUser·p0.9999: 29.428 ms/op
                 existUser·p1.00:   31.949 ms/op

Iteration   3: 5.490 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.651 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  27.484 ms/op
                 existUser·p0.9999: 31.873 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176035
  mean =      5.449 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 75116 
    [ 5.000,  7.500) = 91085 
    [ 7.500, 10.000) = 7510 
    [10.000, 12.500) = 1411 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     23.538 ms/op
     p(99.9900) =     30.939 ms/op
     p(99.9990) =     32.177 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.853 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.789 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.022 ms/op
Iteration   1: 5.683 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.633 ms/op
                 getUser·p0.999:  22.118 ms/op
                 getUser·p0.9999: 24.846 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   2: 5.741 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.528 ms/op
                 getUser·p0.95:   9.306 ms/op
                 getUser·p0.99:   12.616 ms/op
                 getUser·p0.999:  25.262 ms/op
                 getUser·p0.9999: 29.889 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 5.841 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.422 ms/op
                 getUser·p0.95:   8.782 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  17.281 ms/op
                 getUser·p0.9999: 38.176 ms/op
                 getUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166765
  mean =      5.754 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 49162 
    [ 5.000,  7.500) = 102333 
    [ 7.500, 10.000) = 10825 
    [10.000, 12.500) = 2967 
    [12.500, 15.000) = 990 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     21.338 ms/op
     p(99.9900) =     36.064 ms/op
     p(99.9990) =     38.709 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.463 ±(99.9%) 0.441 ms/op
# Warmup Iteration   2: 8.778 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.028 ms/op
Iteration   1: 6.203 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.905 ms/op
                 listUser·p0.999:  24.445 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 6.234 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  30.114 ms/op
                 listUser·p0.9999: 34.865 ms/op
                 listUser·p1.00:   37.749 ms/op

Iteration   3: 6.340 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.174 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  25.377 ms/op
                 listUser·p0.9999: 29.228 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153459
  mean =      6.259 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 11137 
    [ 5.000,  7.500) = 126326 
    [ 7.500, 10.000) = 11632 
    [10.000, 12.500) = 3259 
    [12.500, 15.000) = 640 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.671 ms/op
     p(50.0000) =      5.923 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     33.532 ms/op
     p(99.9990) =     37.363 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.622 ± 6.569  ops/ms
ClientPb.existUser                       thrpt       3   6.001 ± 1.441  ops/ms
ClientPb.getUser                         thrpt       3   5.739 ± 2.919  ops/ms
ClientPb.listUser                        thrpt       3   5.131 ± 5.302  ops/ms
ClientPb.createUser                       avgt       3   5.652 ± 2.083   ms/op
ClientPb.existUser                        avgt       3   5.010 ± 3.172   ms/op
ClientPb.getUser                          avgt       3   5.174 ± 2.925   ms/op
ClientPb.listUser                         avgt       3   6.195 ± 0.636   ms/op
ClientPb.createUser                     sample  163299   5.873 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.228           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.512           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.289           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.317           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.933           ms/op
ClientPb.existUser                      sample  176035   5.449 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.745           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.717           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.660           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.535           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.538           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.939           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  166765   5.754 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.261           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.315           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.338           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.064           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.191           ms/op
ClientPb.listUser                       sample  153459   6.259 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.923           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.846           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.149           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.532           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.749           ms/op
