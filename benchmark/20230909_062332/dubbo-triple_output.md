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
# Warmup Iteration   1: 1.641 ops/ms
# Warmup Iteration   2: 3.885 ops/ms
# Warmup Iteration   3: 6.744 ops/ms
Iteration   1: 7.038 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.548 ±(99.9%) 8.060 ops/ms [Average]
  (min, avg, max) = (7.038, 7.548, 7.817), stdev = 0.442
  CI (99.9%): [≈ 0, 15.609] (assumes normal distribution)


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
# Warmup Iteration   1: 2.391 ops/ms
# Warmup Iteration   2: 6.784 ops/ms
# Warmup Iteration   3: 8.075 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 7.923 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.051 ±(99.9%) 5.357 ops/ms [Average]
  (min, avg, max) = (7.843, 8.051, 8.387), stdev = 0.294
  CI (99.9%): [2.694, 13.408] (assumes normal distribution)


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
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 6.267 ops/ms
# Warmup Iteration   3: 7.469 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 7.758 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.762 ±(99.9%) 0.121 ops/ms [Average]
  (min, avg, max) = (7.757, 7.762, 7.769), stdev = 0.007
  CI (99.9%): [7.640, 7.883] (assumes normal distribution)


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
# Warmup Iteration   1: 1.935 ops/ms
# Warmup Iteration   2: 4.851 ops/ms
# Warmup Iteration   3: 6.293 ops/ms
Iteration   1: 6.398 ops/ms
Iteration   2: 6.220 ops/ms
Iteration   3: 7.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.544 ±(99.9%) 7.611 ops/ms [Average]
  (min, avg, max) = (6.220, 6.544, 7.015), stdev = 0.417
  CI (99.9%): [≈ 0, 14.155] (assumes normal distribution)


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
# Warmup Iteration   1: 13.192 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.006 ms/op
Iteration   1: 4.023 ±(99.9%) 0.005 ms/op
Iteration   2: 4.012 ±(99.9%) 0.006 ms/op
Iteration   3: 4.041 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.025 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (4.012, 4.025, 4.041), stdev = 0.015
  CI (99.9%): [3.756, 4.294] (assumes normal distribution)


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
# Warmup Iteration   1: 13.223 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.007 ms/op
Iteration   1: 3.962 ±(99.9%) 0.004 ms/op
Iteration   2: 3.922 ±(99.9%) 0.003 ms/op
Iteration   3: 3.858 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.914 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (3.858, 3.914, 3.962), stdev = 0.053
  CI (99.9%): [2.953, 4.876] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.607 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.691 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.008 ms/op
Iteration   1: 4.100 ±(99.9%) 0.009 ms/op
Iteration   2: 4.084 ±(99.9%) 0.008 ms/op
Iteration   3: 3.996 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.060 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.996, 4.060, 4.100), stdev = 0.056
  CI (99.9%): [3.035, 5.085] (assumes normal distribution)


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
# Warmup Iteration   1: 15.485 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.118 ±(99.9%) 0.014 ms/op
Iteration   1: 4.980 ±(99.9%) 0.011 ms/op
Iteration   2: 4.908 ±(99.9%) 0.006 ms/op
Iteration   3: 5.170 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.019 ±(99.9%) 2.472 ms/op [Average]
  (min, avg, max) = (4.908, 5.019, 5.170), stdev = 0.135
  CI (99.9%): [2.547, 7.491] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.536 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.148 ±(99.9%) 0.026 ms/op
Iteration   1: 4.369 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  17.498 ms/op
                 createUser·p0.9999: 26.663 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 4.182 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.442 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  14.318 ms/op
                 createUser·p0.9999: 30.977 ms/op
                 createUser·p1.00:   31.916 ms/op

Iteration   3: 4.419 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   9.246 ms/op
                 createUser·p0.999:  31.329 ms/op
                 createUser·p0.9999: 34.652 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222111
  mean =      4.321 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 196232 
    [ 5.000,  7.500) = 21449 
    [ 7.500, 10.000) = 2891 
    [10.000, 12.500) = 814 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     24.205 ms/op
     p(99.9900) =     33.187 ms/op
     p(99.9990) =     34.851 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 13.212 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.861 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.011 ms/op
Iteration   1: 3.955 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.709 ms/op
                 existUser·p0.999:  17.077 ms/op
                 existUser·p0.9999: 25.294 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 4.202 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.942 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  16.807 ms/op
                 existUser·p0.9999: 28.029 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.984 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  26.509 ms/op
                 existUser·p0.9999: 32.635 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237195
  mean =      4.044 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 319 
    [ 2.500,  5.000) = 220314 
    [ 5.000,  7.500) = 13264 
    [ 7.500, 10.000) = 2111 
    [10.000, 12.500) = 590 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     19.484 ms/op
     p(99.9900) =     30.886 ms/op
     p(99.9990) =     33.154 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 12.799 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.015 ms/op
Iteration   1: 4.174 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.064 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  21.770 ms/op
                 getUser·p0.9999: 30.158 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   2: 4.093 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  26.018 ms/op
                 getUser·p0.9999: 28.762 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 4.131 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  13.537 ms/op
                 getUser·p0.9999: 31.181 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232153
  mean =      4.133 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 213460 
    [ 5.000,  7.500) = 15339 
    [ 7.500, 10.000) = 2015 
    [10.000, 12.500) = 735 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     30.526 ms/op
     p(99.9990) =     31.753 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 15.637 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.239 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.142 ±(99.9%) 0.018 ms/op
Iteration   1: 4.967 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  22.968 ms/op
                 listUser·p0.9999: 25.858 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.921 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  17.729 ms/op
                 listUser·p0.9999: 26.526 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 5.105 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  17.968 ms/op
                 listUser·p0.9999: 20.799 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191983
  mean =      4.997 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 135513 
    [ 5.000,  7.500) = 48431 
    [ 7.500, 10.000) = 6096 
    [10.000, 12.500) = 1031 
    [12.500, 15.000) = 356 
    [15.000, 17.500) = 258 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.971 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     19.367 ms/op
     p(99.9900) =     26.044 ms/op
     p(99.9990) =     27.364 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.548 ± 8.060  ops/ms
ClientPb.existUser                       thrpt       3   8.051 ± 5.357  ops/ms
ClientPb.getUser                         thrpt       3   7.762 ± 0.121  ops/ms
ClientPb.listUser                        thrpt       3   6.544 ± 7.611  ops/ms
ClientPb.createUser                       avgt       3   4.025 ± 0.269   ms/op
ClientPb.existUser                        avgt       3   3.914 ± 0.961   ms/op
ClientPb.getUser                          avgt       3   4.060 ± 1.025   ms/op
ClientPb.listUser                         avgt       3   5.019 ± 2.472   ms/op
ClientPb.createUser                     sample  222111   4.321 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.520           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.205           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.187           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  237195   4.044 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.231           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.012           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.484           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.886           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  232153   4.133 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.372           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.526           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  191983   4.997 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.043           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.367           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.044           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
