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
# Warmup Iteration   1: 2.322 ops/ms
# Warmup Iteration   2: 5.524 ops/ms
# Warmup Iteration   3: 8.759 ops/ms
Iteration   1: 9.300 ops/ms
Iteration   2: 9.377 ops/ms
Iteration   3: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.438 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (9.300, 9.438, 9.637), stdev = 0.177
  CI (99.9%): [6.215, 12.660] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 8.724 ops/ms
# Warmup Iteration   3: 9.713 ops/ms
Iteration   1: 9.458 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 9.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.784 ±(99.9%) 5.898 ops/ms [Average]
  (min, avg, max) = (9.458, 9.784, 10.104), stdev = 0.323
  CI (99.9%): [3.886, 15.682] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 8.622 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.635 ±(99.9%) 0.931 ops/ms [Average]
  (min, avg, max) = (9.599, 9.635, 9.694), stdev = 0.051
  CI (99.9%): [8.704, 10.566] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 7.310 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.384 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.254 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (8.151, 8.254, 8.384), stdev = 0.119
  CI (99.9%): [6.089, 10.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.954 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.006 ms/op
Iteration   1: 3.446 ±(99.9%) 0.006 ms/op
Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
Iteration   3: 3.400 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.401 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (3.357, 3.401, 3.446), stdev = 0.044
  CI (99.9%): [2.590, 4.213] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.556 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.002 ms/op
Iteration   1: 3.194 ±(99.9%) 0.004 ms/op
Iteration   2: 3.161 ±(99.9%) 0.011 ms/op
Iteration   3: 3.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.255 ±(99.9%) 2.474 ms/op [Average]
  (min, avg, max) = (3.161, 3.255, 3.410), stdev = 0.136
  CI (99.9%): [0.781, 5.729] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.376 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.005 ms/op
Iteration   1: 3.486 ±(99.9%) 0.003 ms/op
Iteration   2: 3.431 ±(99.9%) 0.004 ms/op
Iteration   3: 3.319 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.319, 3.412, 3.486), stdev = 0.085
  CI (99.9%): [1.866, 4.958] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.213 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.009 ms/op
Iteration   1: 3.838 ±(99.9%) 0.015 ms/op
Iteration   2: 3.929 ±(99.9%) 0.007 ms/op
Iteration   3: 3.910 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.838, 3.893, 3.929), stdev = 0.048
  CI (99.9%): [3.018, 4.768] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.010 ms/op
Iteration   1: 3.474 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.592 ms/op
                 createUser·p0.999:  21.098 ms/op
                 createUser·p0.9999: 24.444 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.333 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  24.510 ms/op
                 createUser·p0.9999: 27.669 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  20.619 ms/op
                 createUser·p0.9999: 26.680 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283805
  mean =      3.381 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5091 
    [ 2.500,  5.000) = 272054 
    [ 5.000,  7.500) = 5325 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     21.469 ms/op
     p(99.9900) =     26.923 ms/op
     p(99.9990) =     28.289 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.426 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.321 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  17.231 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.410 ms/op
                 existUser·p0.999:  16.058 ms/op
                 existUser·p0.9999: 32.724 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293613
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18376 
    [ 2.500,  5.000) = 269009 
    [ 5.000,  7.500) = 5296 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 169 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     14.823 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     33.395 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.549 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.011 ms/op
Iteration   1: 3.545 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 26.738 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  23.904 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.812 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.760 ms/op
                 getUser·p0.999:  23.364 ms/op
                 getUser·p0.9999: 29.326 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278357
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6676 
    [ 2.500,  5.000) = 263020 
    [ 5.000,  7.500) = 7517 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     22.343 ms/op
     p(99.9900) =     28.677 ms/op
     p(99.9990) =     29.924 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.584 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 24.056 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.883 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.703 ms/op
                 listUser·p0.999:  16.464 ms/op
                 listUser·p0.9999: 18.793 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243573
  mean =      3.942 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 236425 
    [ 5.000,  7.500) = 5264 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.438 ± 3.223  ops/ms
ClientPb.existUser                       thrpt       3   9.784 ± 5.898  ops/ms
ClientPb.getUser                         thrpt       3   9.635 ± 0.931  ops/ms
ClientPb.listUser                        thrpt       3   8.254 ± 2.165  ops/ms
ClientPb.createUser                       avgt       3   3.401 ± 0.812   ms/op
ClientPb.existUser                        avgt       3   3.255 ± 2.474   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 1.546   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 0.875   ms/op
ClientPb.createUser                     sample  283805   3.381 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.069           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.469           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.923           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.196           ms/op
ClientPb.existUser                      sample  293613   3.272 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.823           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  278357   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.223           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.343           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  243573   3.942 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
