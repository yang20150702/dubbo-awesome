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
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 3.454 ops/ms
# Warmup Iteration   3: 7.237 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 7.514 ops/ms
Iteration   3: 7.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.552 ±(99.9%) 2.537 ops/ms [Average]
  (min, avg, max) = (7.436, 7.552, 7.706), stdev = 0.139
  CI (99.9%): [5.015, 10.089] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 6.690 ops/ms
# Warmup Iteration   3: 7.946 ops/ms
Iteration   1: 8.178 ops/ms
Iteration   2: 8.273 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.171 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (8.062, 8.171, 8.273), stdev = 0.106
  CI (99.9%): [6.242, 10.099] (assumes normal distribution)


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
# Warmup Iteration   1: 1.812 ops/ms
# Warmup Iteration   2: 6.000 ops/ms
# Warmup Iteration   3: 7.393 ops/ms
Iteration   1: 7.506 ops/ms
Iteration   2: 7.899 ops/ms
Iteration   3: 7.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.783 ±(99.9%) 4.383 ops/ms [Average]
  (min, avg, max) = (7.506, 7.783, 7.943), stdev = 0.240
  CI (99.9%): [3.399, 12.166] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.926 ops/ms
# Warmup Iteration   3: 6.378 ops/ms
Iteration   1: 6.617 ops/ms
Iteration   2: 6.443 ops/ms
Iteration   3: 6.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.523 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (6.443, 6.523, 6.617), stdev = 0.088
  CI (99.9%): [4.917, 8.129] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.151 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.006 ms/op
Iteration   1: 4.165 ±(99.9%) 0.006 ms/op
Iteration   2: 4.088 ±(99.9%) 0.005 ms/op
Iteration   3: 4.076 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.110 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (4.076, 4.110, 4.165), stdev = 0.049
  CI (99.9%): [3.224, 4.995] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.710 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.007 ms/op
Iteration   1: 3.971 ±(99.9%) 0.006 ms/op
Iteration   2: 3.791 ±(99.9%) 0.006 ms/op
Iteration   3: 3.896 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.886 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (3.791, 3.886, 3.971), stdev = 0.090
  CI (99.9%): [2.237, 5.535] (assumes normal distribution)


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
# Warmup Iteration   1: 14.287 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.005 ms/op
Iteration   1: 4.082 ±(99.9%) 0.005 ms/op
Iteration   2: 4.186 ±(99.9%) 0.009 ms/op
Iteration   3: 4.025 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.098 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (4.025, 4.098, 4.186), stdev = 0.082
  CI (99.9%): [2.610, 5.585] (assumes normal distribution)


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
# Warmup Iteration   1: 15.639 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.967 ±(99.9%) 0.006 ms/op
Iteration   1: 4.906 ±(99.9%) 0.008 ms/op
Iteration   2: 4.980 ±(99.9%) 0.008 ms/op
Iteration   3: 5.029 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.971 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (4.906, 4.971, 5.029), stdev = 0.062
  CI (99.9%): [3.843, 6.100] (assumes normal distribution)


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
# Warmup Iteration   1: 13.046 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.215 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.021 ms/op
Iteration   1: 4.286 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   8.592 ms/op
                 createUser·p0.999:  25.326 ms/op
                 createUser·p0.9999: 28.791 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   2: 4.200 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  16.475 ms/op
                 createUser·p0.9999: 28.390 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 4.283 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  30.583 ms/op
                 createUser·p0.9999: 34.834 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225452
  mean =      4.256 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 366 
    [ 2.500,  5.000) = 201828 
    [ 5.000,  7.500) = 18549 
    [ 7.500, 10.000) = 3363 
    [10.000, 12.500) = 783 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     32.959 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.201 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.012 ms/op
Iteration   1: 3.935 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   8.569 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 23.224 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  14.384 ms/op
                 existUser·p0.9999: 28.514 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 4.021 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   6.164 ms/op
                 existUser·p0.99:   8.847 ms/op
                 existUser·p0.999:  16.384 ms/op
                 existUser·p0.9999: 29.953 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244852
  mean =      3.918 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 229464 
    [ 5.000,  7.500) = 10063 
    [ 7.500, 10.000) = 3967 
    [10.000, 12.500) = 595 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     18.402 ms/op
     p(99.9900) =     28.820 ms/op
     p(99.9990) =     30.383 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 13.106 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.019 ms/op
Iteration   1: 4.252 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   7.266 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  24.261 ms/op
                 getUser·p0.9999: 27.309 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   2: 4.107 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  17.470 ms/op
                 getUser·p0.9999: 27.647 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 4.343 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   6.799 ms/op
                 getUser·p0.99:   9.863 ms/op
                 getUser·p0.999:  20.561 ms/op
                 getUser·p0.9999: 31.994 ms/op
                 getUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226702
  mean =      4.232 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 202596 
    [ 5.000,  7.500) = 16226 
    [ 7.500, 10.000) = 5934 
    [10.000, 12.500) = 1151 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     20.916 ms/op
     p(99.9900) =     30.834 ms/op
     p(99.9990) =     32.399 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 16.008 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.001 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.389 ±(99.9%) 0.024 ms/op
Iteration   1: 5.059 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   10.238 ms/op
                 listUser·p0.999:  28.015 ms/op
                 listUser·p0.9999: 30.879 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 5.212 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   4.882 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.787 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  20.904 ms/op
                 listUser·p0.9999: 25.686 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.925 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.719 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  17.962 ms/op
                 listUser·p0.9999: 19.629 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 189478
  mean =      5.063 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 128583 
    [ 5.000,  7.500) = 51030 
    [ 7.500, 10.000) = 7084 
    [10.000, 12.500) = 1835 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     20.892 ms/op
     p(99.9900) =     29.855 ms/op
     p(99.9990) =     31.157 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.552 ± 2.537  ops/ms
ClientPb.existUser                       thrpt       3   8.171 ± 1.928  ops/ms
ClientPb.getUser                         thrpt       3   7.783 ± 4.383  ops/ms
ClientPb.listUser                        thrpt       3   6.523 ± 1.606  ops/ms
ClientPb.createUser                       avgt       3   4.110 ± 0.886   ms/op
ClientPb.existUser                        avgt       3   3.886 ± 1.649   ms/op
ClientPb.getUser                          avgt       3   4.098 ± 1.488   ms/op
ClientPb.listUser                         avgt       3   4.971 ± 1.128   ms/op
ClientPb.createUser                     sample  225452   4.256 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.634           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.919           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.959           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  244852   3.918 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.382           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.402           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.820           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.228           ms/op
ClientPb.getUser                        sample  226702   4.232 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.355           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.916           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.834           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  189478   5.063 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.923           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.600           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.392           ms/op
