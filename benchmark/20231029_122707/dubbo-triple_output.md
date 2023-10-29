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
# Warmup Iteration   1: 1.607 ops/ms
# Warmup Iteration   2: 3.746 ops/ms
# Warmup Iteration   3: 6.793 ops/ms
Iteration   1: 7.519 ops/ms
Iteration   2: 7.534 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.581 ±(99.9%) 1.735 ops/ms [Average]
  (min, avg, max) = (7.519, 7.581, 7.691), stdev = 0.095
  CI (99.9%): [5.846, 9.316] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.085 ops/ms
# Warmup Iteration   2: 6.068 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 8.292 ops/ms
Iteration   3: 8.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.238 ±(99.9%) 3.308 ops/ms [Average]
  (min, avg, max) = (8.035, 8.238, 8.386), stdev = 0.181
  CI (99.9%): [4.930, 11.546] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.775 ops/ms
# Warmup Iteration   3: 7.501 ops/ms
Iteration   1: 7.843 ops/ms
Iteration   2: 7.701 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.945 ±(99.9%) 5.629 ops/ms [Average]
  (min, avg, max) = (7.701, 7.945, 8.292), stdev = 0.309
  CI (99.9%): [2.316, 13.574] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.927 ops/ms
# Warmup Iteration   2: 5.186 ops/ms
# Warmup Iteration   3: 6.510 ops/ms
Iteration   1: 6.274 ops/ms
Iteration   2: 6.005 ops/ms
Iteration   3: 6.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.227 ±(99.9%) 3.700 ops/ms [Average]
  (min, avg, max) = (6.005, 6.227, 6.402), stdev = 0.203
  CI (99.9%): [2.527, 9.927] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.126 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 5.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.005 ms/op
Iteration   1: 4.324 ±(99.9%) 0.006 ms/op
Iteration   2: 4.435 ±(99.9%) 0.007 ms/op
Iteration   3: 4.330 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.363 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (4.324, 4.363, 4.435), stdev = 0.063
  CI (99.9%): [3.221, 5.505] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.495 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.850 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.004 ms/op
Iteration   1: 4.127 ±(99.9%) 0.005 ms/op
Iteration   2: 4.119 ±(99.9%) 0.010 ms/op
Iteration   3: 3.925 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.057 ±(99.9%) 2.091 ms/op [Average]
  (min, avg, max) = (3.925, 4.057, 4.127), stdev = 0.115
  CI (99.9%): [1.966, 6.147] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.067 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.964 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.003 ms/op
Iteration   1: 4.291 ±(99.9%) 0.007 ms/op
Iteration   2: 4.215 ±(99.9%) 0.007 ms/op
Iteration   3: 4.300 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.269 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (4.215, 4.269, 4.300), stdev = 0.046
  CI (99.9%): [3.427, 5.110] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.377 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.912 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.052 ±(99.9%) 0.005 ms/op
Iteration   1: 4.984 ±(99.9%) 0.010 ms/op
Iteration   2: 5.107 ±(99.9%) 0.008 ms/op
Iteration   3: 4.926 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.006 ±(99.9%) 1.679 ms/op [Average]
  (min, avg, max) = (4.926, 5.006, 5.107), stdev = 0.092
  CI (99.9%): [3.326, 6.685] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.388 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.432 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.022 ms/op
Iteration   1: 4.441 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   6.136 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  12.005 ms/op
                 createUser·p0.9999: 30.245 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   2: 4.288 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   8.568 ms/op
                 createUser·p0.999:  26.909 ms/op
                 createUser·p0.9999: 33.212 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   3: 4.826 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   11.158 ms/op
                 createUser·p0.999:  23.421 ms/op
                 createUser·p0.9999: 33.194 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 212944
  mean =      4.507 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 291 
    [ 2.500,  5.000) = 176816 
    [ 5.000,  7.500) = 29679 
    [ 7.500, 10.000) = 4318 
    [10.000, 12.500) = 1302 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 81 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.554 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     25.628 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     33.939 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.096 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.390 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.015 ms/op
Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.584 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  15.008 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 4.214 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.038 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  21.400 ms/op
                 existUser·p0.9999: 33.043 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   3: 4.099 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  29.883 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 232652
  mean =      4.126 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198 
    [ 2.500,  5.000) = 213994 
    [ 5.000,  7.500) = 14356 
    [ 7.500, 10.000) = 2919 
    [10.000, 12.500) = 728 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     21.835 ms/op
     p(99.9900) =     33.087 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.442 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.360 ±(99.9%) 0.016 ms/op
Iteration   1: 4.662 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   7.430 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  17.605 ms/op
                 getUser·p0.9999: 28.873 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 4.446 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  17.796 ms/op
                 getUser·p0.9999: 29.021 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 4.123 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  28.168 ms/op
                 getUser·p0.9999: 31.982 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 218342
  mean =      4.399 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 189519 
    [ 5.000,  7.500) = 21596 
    [ 7.500, 10.000) = 5294 
    [10.000, 12.500) = 1118 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     24.706 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     32.696 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 15.710 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.850 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.171 ±(99.9%) 0.018 ms/op
Iteration   1: 5.136 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.711 ms/op
                 listUser·p0.999:  23.626 ms/op
                 listUser·p0.9999: 26.527 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 4.853 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 25.468 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   3: 4.927 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.658 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 22.398 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193187
  mean =      4.969 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 134664 
    [ 5.000,  7.500) = 53179 
    [ 7.500, 10.000) = 4030 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     21.522 ms/op
     p(99.9900) =     25.745 ms/op
     p(99.9990) =     26.780 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.581 ± 1.735  ops/ms
ClientPb.existUser                       thrpt       3   8.238 ± 3.308  ops/ms
ClientPb.getUser                         thrpt       3   7.945 ± 5.629  ops/ms
ClientPb.listUser                        thrpt       3   6.227 ± 3.700  ops/ms
ClientPb.createUser                       avgt       3   4.363 ± 1.142   ms/op
ClientPb.existUser                        avgt       3   4.057 ± 2.091   ms/op
ClientPb.getUser                          avgt       3   4.269 ± 0.842   ms/op
ClientPb.listUser                         avgt       3   5.006 ± 1.679   ms/op
ClientPb.createUser                     sample  212944   4.507 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.610           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.683           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.628           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.030           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  232652   4.126 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.634           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.835           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  218342   4.399 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.706           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  193187   4.969 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.522           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.745           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
