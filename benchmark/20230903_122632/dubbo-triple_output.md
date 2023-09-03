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
# Warmup Iteration   1: 1.354 ops/ms
# Warmup Iteration   2: 3.310 ops/ms
# Warmup Iteration   3: 6.283 ops/ms
Iteration   1: 6.708 ops/ms
Iteration   2: 6.955 ops/ms
Iteration   3: 6.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.872 ±(99.9%) 2.599 ops/ms [Average]
  (min, avg, max) = (6.708, 6.872, 6.955), stdev = 0.142
  CI (99.9%): [4.273, 9.471] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 5.999 ops/ms
# Warmup Iteration   3: 7.084 ops/ms
Iteration   1: 7.021 ops/ms
Iteration   2: 7.222 ops/ms
Iteration   3: 7.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.149 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (7.021, 7.149, 7.222), stdev = 0.111
  CI (99.9%): [5.121, 9.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.996 ops/ms
# Warmup Iteration   2: 5.890 ops/ms
# Warmup Iteration   3: 6.498 ops/ms
Iteration   1: 6.403 ops/ms
Iteration   2: 6.611 ops/ms
Iteration   3: 6.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.488 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (6.403, 6.488, 6.611), stdev = 0.109
  CI (99.9%): [4.502, 8.474] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 4.907 ops/ms
# Warmup Iteration   3: 5.626 ops/ms
Iteration   1: 5.460 ops/ms
Iteration   2: 5.693 ops/ms
Iteration   3: 5.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.549 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (5.460, 5.549, 5.693), stdev = 0.126
  CI (99.9%): [3.245, 7.852] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.331 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.956 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.011 ms/op
Iteration   1: 5.297 ±(99.9%) 0.012 ms/op
Iteration   2: 4.927 ±(99.9%) 0.017 ms/op
Iteration   3: 4.845 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.023 ±(99.9%) 4.389 ms/op [Average]
  (min, avg, max) = (4.845, 5.023, 5.297), stdev = 0.241
  CI (99.9%): [0.633, 9.412] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.131 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.053 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.531 ±(99.9%) 0.011 ms/op
Iteration   1: 4.548 ±(99.9%) 0.014 ms/op
Iteration   2: 4.625 ±(99.9%) 0.012 ms/op
Iteration   3: 4.572 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.582 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (4.548, 4.582, 4.625), stdev = 0.040
  CI (99.9%): [3.859, 5.304] (assumes normal distribution)


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
# Warmup Iteration   1: 12.020 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.975 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.006 ms/op
Iteration   1: 4.838 ±(99.9%) 0.007 ms/op
Iteration   2: 4.898 ±(99.9%) 0.007 ms/op
Iteration   3: 5.090 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.942 ±(99.9%) 2.398 ms/op [Average]
  (min, avg, max) = (4.838, 4.942, 5.090), stdev = 0.131
  CI (99.9%): [2.544, 7.340] (assumes normal distribution)


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
# Warmup Iteration   1: 15.665 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.218 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.825 ±(99.9%) 0.008 ms/op
Iteration   1: 5.410 ±(99.9%) 0.017 ms/op
Iteration   2: 5.443 ±(99.9%) 0.016 ms/op
Iteration   3: 5.320 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.391 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (5.320, 5.391, 5.443), stdev = 0.063
  CI (99.9%): [4.236, 6.546] (assumes normal distribution)


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
# Warmup Iteration   1: 13.614 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.871 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.333 ±(99.9%) 0.023 ms/op
Iteration   1: 4.901 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   6.735 ms/op
                 createUser·p0.99:   9.234 ms/op
                 createUser·p0.999:  17.220 ms/op
                 createUser·p0.9999: 26.907 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 4.803 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   9.655 ms/op
                 createUser·p0.999:  24.688 ms/op
                 createUser·p0.9999: 32.157 ms/op
                 createUser·p1.00:   33.194 ms/op

Iteration   3: 4.785 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.431 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  24.969 ms/op
                 createUser·p0.9999: 27.644 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 198612
  mean =      4.829 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 137106 
    [ 5.000,  7.500) = 56159 
    [ 7.500, 10.000) = 3780 
    [10.000, 12.500) = 890 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     24.057 ms/op
     p(99.9900) =     30.117 ms/op
     p(99.9990) =     32.903 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 14.568 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.016 ms/op
Iteration   1: 4.751 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.982 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   7.004 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  16.123 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 4.662 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.571 ms/op
                 existUser·p0.95:   6.283 ms/op
                 existUser·p0.99:   9.039 ms/op
                 existUser·p0.999:  14.846 ms/op
                 existUser·p0.9999: 28.943 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 4.688 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  14.988 ms/op
                 existUser·p0.9999: 29.679 ms/op
                 existUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 204230
  mean =      4.700 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 156998 
    [ 5.000,  7.500) = 41281 
    [ 7.500, 10.000) = 4449 
    [10.000, 12.500) = 924 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     28.560 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 14.664 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.570 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.018 ms/op
Iteration   1: 5.095 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.561 ms/op
                 getUser·p0.99:   10.912 ms/op
                 getUser·p0.999:  21.011 ms/op
                 getUser·p0.9999: 27.947 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   2: 4.903 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   5.983 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   10.191 ms/op
                 getUser·p0.999:  23.626 ms/op
                 getUser·p0.9999: 28.260 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   3: 4.869 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.538 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  19.385 ms/op
                 getUser·p0.9999: 29.950 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 193706
  mean =      4.954 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 130014 
    [ 5.000,  7.500) = 54397 
    [ 7.500, 10.000) = 7008 
    [10.000, 12.500) = 1505 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     22.995 ms/op
     p(99.9900) =     28.615 ms/op
     p(99.9990) =     30.229 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 17.222 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.443 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.825 ±(99.9%) 0.021 ms/op
Iteration   1: 5.840 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   11.501 ms/op
                 listUser·p0.999:  24.523 ms/op
                 listUser·p0.9999: 29.508 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 5.432 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  24.056 ms/op
                 listUser·p0.9999: 30.409 ms/op
                 listUser·p1.00:   31.588 ms/op

Iteration   3: 5.605 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.908 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.520 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  18.020 ms/op
                 listUser·p0.9999: 25.732 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 170750
  mean =      5.621 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 47280 
    [ 5.000,  7.500) = 115029 
    [ 7.500, 10.000) = 5747 
    [10.000, 12.500) = 1677 
    [12.500, 15.000) = 428 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     31.287 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.872 ± 2.599  ops/ms
ClientPb.existUser                       thrpt       3   7.149 ± 2.028  ops/ms
ClientPb.getUser                         thrpt       3   6.488 ± 1.986  ops/ms
ClientPb.listUser                        thrpt       3   5.549 ± 2.303  ops/ms
ClientPb.createUser                       avgt       3   5.023 ± 4.389   ms/op
ClientPb.existUser                        avgt       3   4.582 ± 0.723   ms/op
ClientPb.getUser                          avgt       3   4.942 ± 2.398   ms/op
ClientPb.listUser                         avgt       3   5.391 ± 1.155   ms/op
ClientPb.createUser                     sample  198612   4.829 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.561           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.554           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.339           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.057           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.117           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.194           ms/op
ClientPb.existUser                      sample  204230   4.700 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.518           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.560           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.376           ms/op
ClientPb.getUser                        sample  193706   4.954 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.414           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.420           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.995           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  170750   5.621 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.232           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.570           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.305           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.524           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.588           ms/op
