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
# Warmup Iteration   1: 2.334 ops/ms
# Warmup Iteration   2: 5.993 ops/ms
# Warmup Iteration   3: 9.032 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 10.181 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.893 ±(99.9%) 4.617 ops/ms [Average]
  (min, avg, max) = (9.705, 9.893, 10.181), stdev = 0.253
  CI (99.9%): [5.277, 14.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 9.988 ops/ms
Iteration   1: 10.178 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.532 ±(99.9%) 5.598 ops/ms [Average]
  (min, avg, max) = (10.178, 10.532, 10.720), stdev = 0.307
  CI (99.9%): [4.934, 16.130] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 9.979 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 9.999 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.910 ±(99.9%) 4.804 ops/ms [Average]
  (min, avg, max) = (9.614, 9.910, 10.117), stdev = 0.263
  CI (99.9%): [5.106, 14.714] (assumes normal distribution)


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
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.271 ops/ms
Iteration   1: 8.609 ops/ms
Iteration   2: 8.694 ops/ms
Iteration   3: 8.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.641 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (8.609, 8.641, 8.694), stdev = 0.046
  CI (99.9%): [7.798, 9.484] (assumes normal distribution)


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
# Warmup Iteration   1: 7.284 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.004 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
Iteration   3: 3.048 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.116 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.048, 3.116, 3.173), stdev = 0.063
  CI (99.9%): [1.967, 4.265] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.004 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.004 ms/op
Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.096 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.062, 3.096, 3.142), stdev = 0.041
  CI (99.9%): [2.341, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 7.852 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.002 ms/op
Iteration   1: 3.285 ±(99.9%) 0.007 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 3.133 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 1.695 ms/op [Average]
  (min, avg, max) = (3.117, 3.178, 3.285), stdev = 0.093
  CI (99.9%): [1.483, 4.874] (assumes normal distribution)


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
# Warmup Iteration   1: 8.898 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.009 ms/op
Iteration   1: 3.749 ±(99.9%) 0.009 ms/op
Iteration   2: 3.683 ±(99.9%) 0.010 ms/op
Iteration   3: 3.738 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.723 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.683, 3.723, 3.749), stdev = 0.035
  CI (99.9%): [3.080, 4.366] (assumes normal distribution)


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
# Warmup Iteration   1: 8.145 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  13.462 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 21.860 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  14.419 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295066
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26753 
    [ 2.500,  5.000) = 261888 
    [ 5.000,  7.500) = 5603 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.695 ms/op
     p(99.9900) =     23.019 ms/op
     p(99.9990) =     25.369 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 6.521 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.835 ms/op
                 existUser·p0.9999: 22.686 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  13.223 ms/op
                 existUser·p0.9999: 22.295 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302292
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16613 
    [ 2.500,  5.000) = 279749 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.196 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     24.206 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 8.188 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.010 ms/op
Iteration   1: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  12.625 ms/op
                 getUser·p0.9999: 20.010 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   2: 3.215 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  14.012 ms/op
                 getUser·p0.9999: 33.161 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.194 ms/op
                 getUser·p0.999:  11.359 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295220
  mean =      3.250 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15048 
    [ 2.500,  5.000) = 272468 
    [ 5.000,  7.500) = 6608 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 8.621 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
Iteration   1: 3.809 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 32.910 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.434 ms/op

Iteration   3: 3.742 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.347 ms/op
                 listUser·p0.999:  13.838 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253942
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 245185 
    [ 5.000,  7.500) = 6285 
    [ 7.500, 10.000) = 1688 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     14.435 ms/op
     p(99.9900) =     24.938 ms/op
     p(99.9990) =     33.438 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.893 ± 4.617  ops/ms
ClientPb.existUser                       thrpt       3  10.532 ± 5.598  ops/ms
ClientPb.getUser                         thrpt       3   9.910 ± 4.804  ops/ms
ClientPb.listUser                        thrpt       3   8.641 ± 0.843  ops/ms
ClientPb.createUser                       avgt       3   3.116 ± 1.149   ms/op
ClientPb.existUser                        avgt       3   3.096 ± 0.755   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 1.695   ms/op
ClientPb.listUser                         avgt       3   3.723 ± 0.643   ms/op
ClientPb.createUser                     sample  295066   3.252 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.019           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.788           ms/op
ClientPb.existUser                      sample  302292   3.174 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.686           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.196           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  295220   3.250 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.648           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.982           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.227           ms/op
ClientPb.listUser                       sample  253942   3.780 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.435           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.938           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
