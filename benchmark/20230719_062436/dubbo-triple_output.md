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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 6.589 ops/ms
# Warmup Iteration   3: 9.034 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 9.687 ops/ms
Iteration   3: 10.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.955 ±(99.9%) 4.465 ops/ms [Average]
  (min, avg, max) = (9.687, 9.955, 10.165), stdev = 0.245
  CI (99.9%): [5.490, 14.420] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ops/ms
# Warmup Iteration   2: 9.552 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.474 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.420 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (10.333, 10.420, 10.474), stdev = 0.076
  CI (99.9%): [9.031, 11.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ops/ms
# Warmup Iteration   2: 9.166 ops/ms
# Warmup Iteration   3: 9.491 ops/ms
Iteration   1: 9.722 ops/ms
Iteration   2: 10.170 ops/ms
Iteration   3: 9.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.911 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (9.722, 9.911, 10.170), stdev = 0.232
  CI (99.9%): [5.671, 14.150] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.655 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.622 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (8.515, 8.622, 8.695), stdev = 0.094
  CI (99.9%): [6.899, 10.345] (assumes normal distribution)


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.007 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.175 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.175, 3.229, 3.284), stdev = 0.055
  CI (99.9%): [2.227, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 8.200 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.163 ±(99.9%) 0.006 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.062 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.087 ±(99.9%) 1.223 ms/op [Average]
  (min, avg, max) = (3.036, 3.087, 3.163), stdev = 0.067
  CI (99.9%): [1.864, 4.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.004 ms/op
Iteration   1: 3.185 ±(99.9%) 0.008 ms/op
Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
Iteration   3: 3.114 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.152 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.114, 3.152, 3.185), stdev = 0.035
  CI (99.9%): [2.505, 3.799] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.880 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.004 ms/op
Iteration   1: 3.796 ±(99.9%) 0.009 ms/op
Iteration   2: 3.747 ±(99.9%) 0.006 ms/op
Iteration   3: 3.707 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.750 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.707, 3.750, 3.796), stdev = 0.044
  CI (99.9%): [2.938, 4.561] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.984 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
Iteration   1: 3.218 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 22.678 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  12.627 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 22.218 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296567
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21647 
    [ 2.500,  5.000) = 269364 
    [ 5.000,  7.500) = 4787 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     17.963 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     24.282 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.413 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.190 ms/op
                 existUser·p0.9999: 22.829 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 20.043 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 20.648 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304617
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13608 
    [ 2.500,  5.000) = 285117 
    [ 5.000,  7.500) = 5299 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     21.448 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 7.211 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.011 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  9.849 ms/op
                 getUser·p0.9999: 20.877 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   2: 3.274 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  14.176 ms/op
                 getUser·p0.9999: 29.859 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  10.571 ms/op
                 getUser·p0.9999: 23.238 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294846
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18994 
    [ 2.500,  5.000) = 267736 
    [ 5.000,  7.500) = 7450 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.126 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     30.247 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 9.085 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.012 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 24.254 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 3.673 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.059 ms/op
                 listUser·p0.99:   6.640 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 17.397 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.701 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257448
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 250265 
    [ 5.000,  7.500) = 5487 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     13.559 ms/op
     p(99.9900) =     22.766 ms/op
     p(99.9990) =     24.520 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.955 ± 4.465  ops/ms
ClientPb.existUser                       thrpt       3  10.420 ± 1.389  ops/ms
ClientPb.getUser                         thrpt       3   9.911 ± 4.240  ops/ms
ClientPb.listUser                        thrpt       3   8.622 ± 1.723  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 1.002   ms/op
ClientPb.existUser                        avgt       3   3.087 ± 1.223   ms/op
ClientPb.getUser                          avgt       3   3.152 ± 0.647   ms/op
ClientPb.listUser                         avgt       3   3.750 ± 0.811   ms/op
ClientPb.createUser                     sample  296567   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.963           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  304617   3.148 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.448           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.429           ms/op
ClientPb.getUser                        sample  294846   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.126           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  257448   3.726 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.110           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.559           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.766           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
