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
# Warmup Iteration   1: 2.189 ops/ms
# Warmup Iteration   2: 5.564 ops/ms
# Warmup Iteration   3: 8.986 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 9.732 ops/ms
Iteration   3: 9.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.577 ±(99.9%) 3.722 ops/ms [Average]
  (min, avg, max) = (9.346, 9.577, 9.732), stdev = 0.204
  CI (99.9%): [5.855, 13.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 9.798 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.819 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (9.615, 9.819, 9.954), stdev = 0.179
  CI (99.9%): [6.549, 13.088] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 8.809 ops/ms
# Warmup Iteration   3: 9.406 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.559 ops/ms
Iteration   3: 9.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.471 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (9.291, 9.471, 9.563), stdev = 0.156
  CI (99.9%): [6.622, 12.320] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 7.241 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.099 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.194 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (8.099, 8.194, 8.275), stdev = 0.089
  CI (99.9%): [6.566, 9.822] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.624 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.003 ms/op
Iteration   1: 3.455 ±(99.9%) 0.009 ms/op
Iteration   2: 3.420 ±(99.9%) 0.005 ms/op
Iteration   3: 3.364 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.413 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.364, 3.413, 3.455), stdev = 0.046
  CI (99.9%): [2.581, 4.245] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
Iteration   1: 3.200 ±(99.9%) 0.006 ms/op
Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
Iteration   3: 3.290 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (3.200, 3.259, 3.290), stdev = 0.051
  CI (99.9%): [2.326, 4.193] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.018 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.004 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.288 ±(99.9%) 0.005 ms/op
Iteration   3: 3.319 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.335 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.288, 3.335, 3.398), stdev = 0.057
  CI (99.9%): [2.301, 4.368] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.191 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.010 ms/op
Iteration   1: 3.827 ±(99.9%) 0.013 ms/op
Iteration   2: 3.960 ±(99.9%) 0.007 ms/op
Iteration   3: 3.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.916 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.827, 3.916, 3.961), stdev = 0.077
  CI (99.9%): [2.514, 5.317] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.922 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.011 ms/op
Iteration   1: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 23.977 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  22.023 ms/op
                 createUser·p0.9999: 28.882 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  19.604 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278574
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11510 
    [ 2.500,  5.000) = 259279 
    [ 5.000,  7.500) = 6867 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     19.820 ms/op
     p(99.9900) =     28.003 ms/op
     p(99.9990) =     29.760 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  12.177 ms/op
                 existUser·p0.9999: 22.032 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  10.917 ms/op
                 existUser·p0.9999: 24.017 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.235 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.866 ms/op
                 existUser·p0.9999: 21.467 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295245
  mean =      3.249 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12257 
    [ 2.500,  5.000) = 278275 
    [ 5.000,  7.500) = 3872 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 165 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     10.629 ms/op
     p(99.9900) =     22.888 ms/op
     p(99.9990) =     24.985 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.132 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.598 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.362 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.031 ms/op
                 getUser·p0.999:  22.188 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.303 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  11.689 ms/op
                 getUser·p0.9999: 26.825 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.797 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  19.445 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275526
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8203 
    [ 2.500,  5.000) = 257004 
    [ 5.000,  7.500) = 9081 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     21.085 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.114 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.106 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
Iteration   1: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  21.139 ms/op
                 listUser·p0.9999: 24.571 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.916 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.345 ms/op
                 listUser·p0.9999: 15.177 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.366 ms/op
                 listUser·p0.999:  14.498 ms/op
                 listUser·p0.9999: 19.987 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243246
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 235466 
    [ 5.000,  7.500) = 5534 
    [ 7.500, 10.000) = 1480 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.287 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     24.238 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.577 ± 3.722  ops/ms
ClientPb.existUser                       thrpt       3   9.819 ± 3.269  ops/ms
ClientPb.getUser                         thrpt       3   9.471 ± 2.849  ops/ms
ClientPb.listUser                        thrpt       3   8.194 ± 1.628  ops/ms
ClientPb.createUser                       avgt       3   3.413 ± 0.832   ms/op
ClientPb.existUser                        avgt       3   3.259 ± 0.934   ms/op
ClientPb.getUser                          avgt       3   3.335 ± 1.033   ms/op
ClientPb.listUser                         avgt       3   3.916 ± 1.401   ms/op
ClientPb.createUser                     sample  278574   3.445 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.833           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.820           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.003           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.081           ms/op
ClientPb.existUser                      sample  295245   3.249 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.629           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  275526   3.483 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.362           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.280           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.329           ms/op
ClientPb.listUser                       sample  243246   3.948 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.329           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.287           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.238           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
