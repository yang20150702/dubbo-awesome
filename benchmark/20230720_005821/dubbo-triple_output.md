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
# Warmup Iteration   1: 2.444 ops/ms
# Warmup Iteration   2: 5.622 ops/ms
# Warmup Iteration   3: 8.784 ops/ms
Iteration   1: 9.570 ops/ms
Iteration   2: 9.532 ops/ms
Iteration   3: 9.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.637 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (9.532, 9.637, 9.810), stdev = 0.151
  CI (99.9%): [6.891, 12.383] (assumes normal distribution)


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
# Warmup Iteration   1: 3.272 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 10.094 ops/ms
Iteration   1: 10.074 ops/ms
Iteration   2: 10.014 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.203 ±(99.9%) 5.065 ops/ms [Average]
  (min, avg, max) = (10.014, 10.203, 10.522), stdev = 0.278
  CI (99.9%): [5.139, 15.268] (assumes normal distribution)


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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.053 ops/ms
# Warmup Iteration   3: 9.666 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 9.881 ops/ms
Iteration   3: 9.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.984 ±(99.9%) 2.275 ops/ms [Average]
  (min, avg, max) = (9.881, 9.984, 10.122), stdev = 0.125
  CI (99.9%): [7.709, 12.259] (assumes normal distribution)


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
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 7.455 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.307 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.406 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (8.307, 8.406, 8.580), stdev = 0.151
  CI (99.9%): [5.651, 11.162] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.543 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.006 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
Iteration   2: 3.203 ±(99.9%) 0.004 ms/op
Iteration   3: 3.300 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.196, 3.233, 3.300), stdev = 0.058
  CI (99.9%): [2.171, 4.295] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.009 ms/op
Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
Iteration   3: 3.188 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.214 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.188, 3.214, 3.249), stdev = 0.032
  CI (99.9%): [2.634, 3.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.006 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.253 ±(99.9%) 0.005 ms/op
Iteration   3: 3.345 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.196, 3.265, 3.345), stdev = 0.075
  CI (99.9%): [1.895, 4.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.704 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.005 ms/op
Iteration   1: 3.717 ±(99.9%) 0.012 ms/op
Iteration   2: 3.682 ±(99.9%) 0.011 ms/op
Iteration   3: 3.699 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.699 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.682, 3.699, 3.717), stdev = 0.018
  CI (99.9%): [3.375, 4.024] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.465 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
Iteration   1: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 24.260 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   2: 3.201 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 28.709 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.679 ms/op
                 createUser·p0.9999: 25.987 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300391
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15673 
    [ 2.500,  5.000) = 279960 
    [ 5.000,  7.500) = 3814 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     16.689 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 8.085 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
Iteration   1: 3.216 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.738 ms/op
                 existUser·p0.9999: 18.750 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  10.066 ms/op
                 existUser·p0.9999: 22.740 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.879 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 20.849 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302504
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21670 
    [ 2.500,  5.000) = 275540 
    [ 5.000,  7.500) = 4553 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.458 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.455 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.011 ms/op
Iteration   1: 3.408 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.520 ms/op
                 getUser·p0.999:  18.058 ms/op
                 getUser·p0.9999: 26.504 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  10.999 ms/op
                 getUser·p0.9999: 24.780 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  14.227 ms/op
                 getUser·p0.9999: 22.294 ms/op
                 getUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287997
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11804 
    [ 2.500,  5.000) = 268422 
    [ 5.000,  7.500) = 6830 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.275 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.018 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.013 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 20.957 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.925 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 15.459 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   3: 3.882 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 15.951 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246250
  mean =      3.899 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 236445 
    [ 5.000,  7.500) = 7955 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     20.361 ms/op
     p(99.9990) =     21.906 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.637 ± 2.746  ops/ms
ClientPb.existUser                       thrpt       3  10.203 ± 5.065  ops/ms
ClientPb.getUser                         thrpt       3   9.984 ± 2.275  ops/ms
ClientPb.listUser                        thrpt       3   8.406 ± 2.756  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 1.062   ms/op
ClientPb.existUser                        avgt       3   3.214 ± 0.580   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 1.370   ms/op
ClientPb.listUser                         avgt       3   3.699 ± 0.324   ms/op
ClientPb.createUser                     sample  300391   3.193 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.120           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.689           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.951           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.081           ms/op
ClientPb.existUser                      sample  302504   3.173 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  287997   3.332 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.873           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.133           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.427           ms/op
ClientPb.listUser                       sample  246250   3.899 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.227           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.361           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
