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
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 3.332 ops/ms
# Warmup Iteration   3: 6.219 ops/ms
Iteration   1: 7.522 ops/ms
Iteration   2: 8.046 ops/ms
Iteration   3: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.779 ±(99.9%) 4.785 ops/ms [Average]
  (min, avg, max) = (7.522, 7.779, 8.046), stdev = 0.262
  CI (99.9%): [2.993, 12.564] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 5.984 ops/ms
# Warmup Iteration   3: 7.215 ops/ms
Iteration   1: 7.973 ops/ms
Iteration   2: 8.542 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.232 ±(99.9%) 5.257 ops/ms [Average]
  (min, avg, max) = (7.973, 8.232, 8.542), stdev = 0.288
  CI (99.9%): [2.975, 13.488] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.135 ops/ms
# Warmup Iteration   2: 5.816 ops/ms
# Warmup Iteration   3: 7.477 ops/ms
Iteration   1: 7.506 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 7.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.602 ±(99.9%) 4.452 ops/ms [Average]
  (min, avg, max) = (7.420, 7.602, 7.879), stdev = 0.244
  CI (99.9%): [3.150, 12.054] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.962 ops/ms
# Warmup Iteration   2: 5.368 ops/ms
# Warmup Iteration   3: 6.209 ops/ms
Iteration   1: 6.289 ops/ms
Iteration   2: 6.121 ops/ms
Iteration   3: 6.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.351 ±(99.9%) 4.857 ops/ms [Average]
  (min, avg, max) = (6.121, 6.351, 6.643), stdev = 0.266
  CI (99.9%): [1.494, 11.208] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.606 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.007 ms/op
Iteration   1: 4.278 ±(99.9%) 0.005 ms/op
Iteration   2: 4.155 ±(99.9%) 0.005 ms/op
Iteration   3: 4.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.167 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (4.068, 4.167, 4.278), stdev = 0.105
  CI (99.9%): [2.246, 6.088] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.989 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.723 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.004 ms/op
Iteration   1: 3.940 ±(99.9%) 0.005 ms/op
Iteration   2: 4.151 ±(99.9%) 0.007 ms/op
Iteration   3: 3.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.006 ±(99.9%) 2.291 ms/op [Average]
  (min, avg, max) = (3.928, 4.006, 4.151), stdev = 0.126
  CI (99.9%): [1.715, 6.298] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.895 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.392 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.003 ms/op
Iteration   1: 4.063 ±(99.9%) 0.006 ms/op
Iteration   2: 4.095 ±(99.9%) 0.009 ms/op
Iteration   3: 4.203 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.120 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (4.063, 4.120, 4.203), stdev = 0.073
  CI (99.9%): [2.786, 5.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.465 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.011 ms/op
Iteration   1: 4.742 ±(99.9%) 0.011 ms/op
Iteration   2: 4.811 ±(99.9%) 0.009 ms/op
Iteration   3: 4.699 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.751 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (4.699, 4.751, 4.811), stdev = 0.057
  CI (99.9%): [3.719, 5.782] (assumes normal distribution)


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
# Warmup Iteration   1: 13.116 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.850 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.019 ms/op
Iteration   1: 3.896 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  22.670 ms/op
                 createUser·p0.9999: 27.092 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 3.970 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.966 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 30.337 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 4.019 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.417 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  28.635 ms/op
                 createUser·p0.9999: 33.361 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242186
  mean =      3.961 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 230009 
    [ 5.000,  7.500) = 9384 
    [ 7.500, 10.000) = 1904 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     22.663 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     34.233 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 11.491 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  12.856 ms/op
                 existUser·p0.9999: 25.030 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 4.050 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  25.592 ms/op
                 existUser·p0.9999: 29.819 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   3: 3.983 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   7.661 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 38.001 ms/op
                 existUser·p1.00:   38.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241687
  mean =      3.974 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 228023 
    [ 5.000,  7.500) = 10360 
    [ 7.500, 10.000) = 2109 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     18.295 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     38.464 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


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
# Warmup Iteration   1: 14.936 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.016 ms/op
Iteration   1: 4.205 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.171 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   6.619 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  20.043 ms/op
                 getUser·p0.9999: 32.380 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 4.160 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  25.530 ms/op
                 getUser·p0.9999: 28.025 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  13.718 ms/op
                 getUser·p0.9999: 30.680 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232356
  mean =      4.130 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 212142 
    [ 5.000,  7.500) = 14710 
    [ 7.500, 10.000) = 3965 
    [10.000, 12.500) = 1081 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     22.051 ms/op
     p(99.9900) =     31.212 ms/op
     p(99.9990) =     32.626 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 17.082 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.970 ±(99.9%) 0.020 ms/op
Iteration   1: 4.961 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  25.249 ms/op
                 listUser·p0.9999: 28.869 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 4.811 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  20.007 ms/op
                 listUser·p0.9999: 26.357 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 4.663 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.793 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.962 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199543
  mean =      4.809 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 164232 
    [ 5.000,  7.500) = 28799 
    [ 7.500, 10.000) = 4495 
    [10.000, 12.500) = 1117 
    [12.500, 15.000) = 410 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     19.542 ms/op
     p(99.9900) =     27.002 ms/op
     p(99.9990) =     30.442 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.779 ± 4.785  ops/ms
ClientPb.existUser                       thrpt       3   8.232 ± 5.257  ops/ms
ClientPb.getUser                         thrpt       3   7.602 ± 4.452  ops/ms
ClientPb.listUser                        thrpt       3   6.351 ± 4.857  ops/ms
ClientPb.createUser                       avgt       3   4.167 ± 1.921   ms/op
ClientPb.existUser                        avgt       3   4.006 ± 2.291   ms/op
ClientPb.getUser                          avgt       3   4.120 ± 1.335   ms/op
ClientPb.listUser                         avgt       3   4.751 ± 1.031   ms/op
ClientPb.createUser                     sample  242186   3.961 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.989           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.663           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.440           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  241687   3.974 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.938           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.295           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.994           ms/op
ClientPb.getUser                        sample  232356   4.130 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.110           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.051           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  199543   4.809 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.165           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.542           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.002           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.474           ms/op
