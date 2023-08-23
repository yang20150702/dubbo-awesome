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
# Warmup Iteration   1: 2.043 ops/ms
# Warmup Iteration   2: 5.691 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 9.277 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.226 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (9.122, 9.226, 9.279), stdev = 0.090
  CI (99.9%): [7.585, 10.867] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 8.922 ops/ms
# Warmup Iteration   3: 9.564 ops/ms
Iteration   1: 9.272 ops/ms
Iteration   2: 9.179 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.264 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (9.179, 9.264, 9.340), stdev = 0.081
  CI (99.9%): [7.786, 10.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 6.929 ops/ms
# Warmup Iteration   3: 8.615 ops/ms
Iteration   1: 9.098 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 9.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.082 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (9.047, 9.082, 9.101), stdev = 0.030
  CI (99.9%): [8.528, 9.636] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 6.944 ops/ms
# Warmup Iteration   3: 7.440 ops/ms
Iteration   1: 7.547 ops/ms
Iteration   2: 7.844 ops/ms
Iteration   3: 7.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.770 ±(99.9%) 3.595 ops/ms [Average]
  (min, avg, max) = (7.547, 7.770, 7.920), stdev = 0.197
  CI (99.9%): [4.175, 11.366] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.337 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.005 ms/op
Iteration   1: 3.469 ±(99.9%) 0.007 ms/op
Iteration   2: 3.600 ±(99.9%) 0.006 ms/op
Iteration   3: 3.380 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.483 ±(99.9%) 2.028 ms/op [Average]
  (min, avg, max) = (3.380, 3.483, 3.600), stdev = 0.111
  CI (99.9%): [1.455, 5.510] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.601 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.003 ms/op
Iteration   1: 3.431 ±(99.9%) 0.005 ms/op
Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
Iteration   3: 3.448 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.424 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.393, 3.424, 3.448), stdev = 0.028
  CI (99.9%): [2.908, 3.940] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.079 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.003 ms/op
Iteration   1: 3.438 ±(99.9%) 0.008 ms/op
Iteration   2: 3.396 ±(99.9%) 0.003 ms/op
Iteration   3: 3.438 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.424 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.396, 3.424, 3.438), stdev = 0.024
  CI (99.9%): [2.986, 3.862] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.396 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.005 ms/op
Iteration   1: 4.100 ±(99.9%) 0.009 ms/op
Iteration   2: 3.972 ±(99.9%) 0.014 ms/op
Iteration   3: 4.061 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.045 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.972, 4.045, 4.100), stdev = 0.065
  CI (99.9%): [2.850, 5.239] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.243 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.012 ms/op
Iteration   1: 3.521 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  23.167 ms/op
                 createUser·p0.9999: 25.392 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 30.704 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 3.450 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  21.395 ms/op
                 createUser·p0.9999: 33.522 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274124
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8386 
    [ 2.500,  5.000) = 258964 
    [ 5.000,  7.500) = 5476 
    [ 7.500, 10.000) = 815 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     18.379 ms/op
     p(99.9900) =     32.438 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.552 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.500 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  21.201 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  22.638 ms/op
                 existUser·p0.9999: 28.635 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   3: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 29.098 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280139
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5751 
    [ 2.500,  5.000) = 265858 
    [ 5.000,  7.500) = 6729 
    [ 7.500, 10.000) = 1223 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.678 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     29.727 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.844 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.014 ms/op
Iteration   1: 3.553 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.362 ms/op
                 getUser·p0.999:  22.379 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.487 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  23.734 ms/op
                 getUser·p0.9999: 26.400 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.665 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  22.963 ms/op
                 getUser·p0.9999: 27.927 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268974
  mean =      3.567 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6131 
    [ 2.500,  5.000) = 250314 
    [ 5.000,  7.500) = 10407 
    [ 7.500, 10.000) = 1471 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     22.544 ms/op
     p(99.9900) =     27.034 ms/op
     p(99.9990) =     28.682 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.553 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.015 ms/op
Iteration   1: 4.184 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  22.335 ms/op
                 listUser·p0.9999: 27.250 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.215 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 29.863 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   3: 4.148 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  15.901 ms/op
                 listUser·p0.9999: 21.186 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229452
  mean =      4.182 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 216361 
    [ 5.000,  7.500) = 9392 
    [ 7.500, 10.000) = 2541 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     17.501 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     30.318 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.226 ± 1.641  ops/ms
ClientPb.existUser                       thrpt       3   9.264 ± 1.477  ops/ms
ClientPb.getUser                         thrpt       3   9.082 ± 0.554  ops/ms
ClientPb.listUser                        thrpt       3   7.770 ± 3.595  ops/ms
ClientPb.createUser                       avgt       3   3.483 ± 2.028   ms/op
ClientPb.existUser                        avgt       3   3.424 ± 0.516   ms/op
ClientPb.getUser                          avgt       3   3.424 ± 0.438   ms/op
ClientPb.listUser                         avgt       3   4.045 ± 1.194   ms/op
ClientPb.createUser                     sample  274124   3.498 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.495           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.438           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  280139   3.427 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.016           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.678           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.672           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.147           ms/op
ClientPb.getUser                        sample  268974   3.567 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.274           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.544           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.034           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  229452   4.182 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.501           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.066           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.097           ms/op
