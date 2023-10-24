# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.543 ops/ms
# Warmup Iteration   2: 3.162 ops/ms
# Warmup Iteration   3: 6.735 ops/ms
Iteration   1: 7.254 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 7.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.632 ±(99.9%) 6.155 ops/ms [Average]
  (min, avg, max) = (7.254, 7.632, 7.904), stdev = 0.337
  CI (99.9%): [1.477, 13.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.049 ops/ms
# Warmup Iteration   2: 6.452 ops/ms
# Warmup Iteration   3: 7.691 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 8.168 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.138 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (8.022, 8.138, 8.225), stdev = 0.104
  CI (99.9%): [6.232, 10.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.049 ops/ms
# Warmup Iteration   2: 5.231 ops/ms
# Warmup Iteration   3: 7.753 ops/ms
Iteration   1: 7.561 ops/ms
Iteration   2: 7.771 ops/ms
Iteration   3: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.710 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (7.561, 7.710, 7.799), stdev = 0.130
  CI (99.9%): [5.339, 10.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
# Warmup Iteration   2: 5.320 ops/ms
# Warmup Iteration   3: 6.240 ops/ms
Iteration   1: 6.484 ops/ms
Iteration   2: 6.540 ops/ms
Iteration   3: 6.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.529 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (6.484, 6.529, 6.562), stdev = 0.040
  CI (99.9%): [5.791, 7.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.241 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.286 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.327 ±(99.9%) 0.005 ms/op
Iteration   1: 4.326 ±(99.9%) 0.004 ms/op
Iteration   2: 4.205 ±(99.9%) 0.004 ms/op
Iteration   3: 4.141 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.224 ±(99.9%) 1.712 ms/op [Average]
  (min, avg, max) = (4.141, 4.224, 4.326), stdev = 0.094
  CI (99.9%): [2.512, 5.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.293 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.003 ms/op
Iteration   1: 3.902 ±(99.9%) 0.005 ms/op
Iteration   2: 3.965 ±(99.9%) 0.004 ms/op
Iteration   3: 3.905 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.924 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.902, 3.924, 3.965), stdev = 0.036
  CI (99.9%): [3.273, 4.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.891 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.004 ms/op
Iteration   1: 4.121 ±(99.9%) 0.004 ms/op
Iteration   2: 3.932 ±(99.9%) 0.005 ms/op
Iteration   3: 4.134 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.062 ±(99.9%) 2.064 ms/op [Average]
  (min, avg, max) = (3.932, 4.062, 4.134), stdev = 0.113
  CI (99.9%): [1.999, 6.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.252 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.917 ±(99.9%) 0.007 ms/op
Iteration   1: 4.816 ±(99.9%) 0.007 ms/op
Iteration   2: 4.991 ±(99.9%) 0.008 ms/op
Iteration   3: 5.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.941 ±(99.9%) 1.991 ms/op [Average]
  (min, avg, max) = (4.816, 4.941, 5.017), stdev = 0.109
  CI (99.9%): [2.951, 6.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.099 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.661 ±(99.9%) 0.023 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.954 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  16.438 ms/op
                 createUser·p0.9999: 26.777 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 32.969 ms/op
                 createUser·p1.00:   34.144 ms/op

Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  27.197 ms/op
                 createUser·p0.9999: 29.749 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236252
  mean =      4.055 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 224975 
    [ 5.000,  7.500) = 9073 
    [ 7.500, 10.000) = 1333 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 147 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     30.077 ms/op
     p(99.9990) =     33.984 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 13.290 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.081 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   7.881 ms/op
                 existUser·p0.999:  13.456 ms/op
                 existUser·p0.9999: 25.411 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 27.165 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241412
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 229471 
    [ 5.000,  7.500) = 9421 
    [ 7.500, 10.000) = 1867 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.486 ms/op
     p(99.9000) =     12.674 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.542 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.883 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 5.360 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.015 ms/op
Iteration   1: 4.283 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   9.142 ms/op
                 getUser·p0.999:  14.828 ms/op
                 getUser·p0.9999: 29.101 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 4.177 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  25.442 ms/op
                 getUser·p0.9999: 28.519 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 4.134 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  14.789 ms/op
                 getUser·p0.9999: 31.180 ms/op
                 getUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228464
  mean =      4.197 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 209995 
    [ 5.000,  7.500) = 13125 
    [ 7.500, 10.000) = 4191 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     23.517 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.089 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.481 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.015 ±(99.9%) 0.017 ms/op
Iteration   1: 4.963 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  25.315 ms/op
                 listUser·p0.9999: 29.036 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   2: 4.935 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.204 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  22.829 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 4.764 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 20.621 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196391
  mean =      4.886 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 145244 
    [ 5.000,  7.500) = 46712 
    [ 7.500, 10.000) = 3156 
    [10.000, 12.500) = 561 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      9.094 ms/op
     p(99.9000) =     22.624 ms/op
     p(99.9900) =     33.402 ms/op
     p(99.9990) =     35.457 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.632 ± 6.155  ops/ms
ClientPb.existUser                       thrpt       3   8.138 ± 1.906  ops/ms
ClientPb.getUser                         thrpt       3   7.710 ± 2.371  ops/ms
ClientPb.listUser                        thrpt       3   6.529 ± 0.737  ops/ms
ClientPb.createUser                       avgt       3   4.224 ± 1.712   ms/op
ClientPb.existUser                        avgt       3   3.924 ± 0.651   ms/op
ClientPb.getUser                          avgt       3   4.062 ± 2.064   ms/op
ClientPb.listUser                         avgt       3   4.941 ± 1.991   ms/op
ClientPb.createUser                     sample  236252   4.055 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.716           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.395           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.077           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  241412   3.973 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.486           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.674           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.247           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.722           ms/op
ClientPb.getUser                        sample  228464   4.197 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.686           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.667           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.517           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  196391   4.886 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.043           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.624           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.402           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.521           ms/op
