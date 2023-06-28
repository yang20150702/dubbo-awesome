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
# Warmup Iteration   1: 0.933 ops/ms
# Warmup Iteration   2: 2.501 ops/ms
# Warmup Iteration   3: 4.998 ops/ms
Iteration   1: 5.319 ops/ms
Iteration   2: 5.354 ops/ms
Iteration   3: 5.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.396 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (5.319, 5.396, 5.515), stdev = 0.104
  CI (99.9%): [3.490, 7.302] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 4.626 ops/ms
# Warmup Iteration   3: 5.576 ops/ms
Iteration   1: 5.826 ops/ms
Iteration   2: 5.743 ops/ms
Iteration   3: 5.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.807 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (5.743, 5.807, 5.852), stdev = 0.057
  CI (99.9%): [4.768, 6.846] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.607 ops/ms
# Warmup Iteration   3: 5.499 ops/ms
Iteration   1: 5.552 ops/ms
Iteration   2: 5.382 ops/ms
Iteration   3: 5.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.507 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (5.382, 5.507, 5.587), stdev = 0.110
  CI (99.9%): [3.503, 7.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.469 ops/ms
# Warmup Iteration   2: 4.050 ops/ms
# Warmup Iteration   3: 4.864 ops/ms
Iteration   1: 4.679 ops/ms
Iteration   2: 4.870 ops/ms
Iteration   3: 4.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.745 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (4.679, 4.745, 4.870), stdev = 0.108
  CI (99.9%): [2.766, 6.724] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.889 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.484 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.016 ±(99.9%) 0.019 ms/op
Iteration   1: 5.907 ±(99.9%) 0.021 ms/op
Iteration   2: 5.841 ±(99.9%) 0.012 ms/op
Iteration   3: 5.959 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.902 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (5.841, 5.902, 5.959), stdev = 0.059
  CI (99.9%): [4.828, 6.977] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.719 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.175 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.008 ms/op
Iteration   1: 5.543 ±(99.9%) 0.012 ms/op
Iteration   2: 5.602 ±(99.9%) 0.014 ms/op
Iteration   3: 5.401 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.516 ±(99.9%) 1.892 ms/op [Average]
  (min, avg, max) = (5.401, 5.516, 5.602), stdev = 0.104
  CI (99.9%): [3.623, 7.408] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.250 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.016 ms/op
Iteration   1: 5.912 ±(99.9%) 0.013 ms/op
Iteration   2: 5.862 ±(99.9%) 0.017 ms/op
Iteration   3: 5.846 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.873 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (5.846, 5.873, 5.912), stdev = 0.034
  CI (99.9%): [5.251, 6.496] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.308 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 8.699 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.861 ±(99.9%) 0.012 ms/op
Iteration   1: 6.983 ±(99.9%) 0.013 ms/op
Iteration   2: 6.963 ±(99.9%) 0.017 ms/op
Iteration   3: 6.892 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.946 ±(99.9%) 0.874 ms/op [Average]
  (min, avg, max) = (6.892, 6.946, 6.983), stdev = 0.048
  CI (99.9%): [6.072, 7.820] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.269 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 7.635 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.087 ±(99.9%) 0.028 ms/op
Iteration   1: 6.098 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   5.906 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  15.319 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 5.843 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   8.356 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  26.148 ms/op
                 createUser·p0.9999: 29.460 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 6.071 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   5.857 ms/op
                 createUser·p0.90:   7.512 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  29.180 ms/op
                 createUser·p0.9999: 33.948 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159796
  mean =      6.002 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 32725 
    [ 5.000,  7.500) = 111139 
    [ 7.500, 10.000) = 13331 
    [10.000, 12.500) = 1993 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     25.199 ms/op
     p(99.9900) =     31.852 ms/op
     p(99.9990) =     34.920 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.129 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.883 ±(99.9%) 0.020 ms/op
Iteration   1: 5.645 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.331 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  14.784 ms/op
                 existUser·p0.9999: 25.668 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 5.506 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.250 ms/op
                 existUser·p0.99:   10.781 ms/op
                 existUser·p0.999:  25.327 ms/op
                 existUser·p0.9999: 32.295 ms/op
                 existUser·p1.00:   33.358 ms/op

Iteration   3: 5.512 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.363 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   7.920 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  29.065 ms/op
                 existUser·p0.9999: 33.240 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172712
  mean =      5.554 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 71058 
    [ 5.000,  7.500) = 90788 
    [ 7.500, 10.000) = 8325 
    [10.000, 12.500) = 1811 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     16.979 ms/op
     p(99.9900) =     32.759 ms/op
     p(99.9990) =     35.443 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 18.534 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 7.282 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.013 ±(99.9%) 0.023 ms/op
Iteration   1: 6.004 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   5.718 ms/op
                 getUser·p0.90:   7.496 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  16.347 ms/op
                 getUser·p0.9999: 26.314 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 5.884 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.013 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.380 ms/op
                 getUser·p0.99:   11.644 ms/op
                 getUser·p0.999:  25.699 ms/op
                 getUser·p0.9999: 29.823 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 5.803 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.269 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  24.743 ms/op
                 getUser·p0.9999: 30.572 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162751
  mean =      5.896 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 37347 
    [ 5.000,  7.500) = 111247 
    [ 7.500, 10.000) = 11800 
    [10.000, 12.500) = 1584 
    [12.500, 15.000) = 435 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     22.069 ms/op
     p(99.9900) =     29.875 ms/op
     p(99.9990) =     31.410 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 20.100 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 8.712 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.949 ±(99.9%) 0.029 ms/op
Iteration   1: 6.845 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.166 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.332 ms/op
                 listUser·p0.999:  24.880 ms/op
                 listUser·p0.9999: 28.218 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 6.706 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.273 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 30.308 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   3: 6.983 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   6.652 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  26.547 ms/op
                 listUser·p0.9999: 48.038 ms/op
                 listUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140242
  mean =      6.843 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3322 
    [ 5.000, 10.000) = 131799 
    [10.000, 15.000) = 4510 
    [15.000, 20.000) = 319 
    [20.000, 25.000) = 105 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      3.166 ms/op
     p(50.0000) =      6.537 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.503 ms/op
     p(99.0000) =     12.265 ms/op
     p(99.9000) =     25.879 ms/op
     p(99.9900) =     43.906 ms/op
     p(99.9990) =     48.443 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.396 ± 1.906  ops/ms
ClientPb.existUser                       thrpt       3   5.807 ± 1.039  ops/ms
ClientPb.getUser                         thrpt       3   5.507 ± 2.004  ops/ms
ClientPb.listUser                        thrpt       3   4.745 ± 1.979  ops/ms
ClientPb.createUser                       avgt       3   5.902 ± 1.074   ms/op
ClientPb.existUser                        avgt       3   5.516 ± 1.892   ms/op
ClientPb.getUser                          avgt       3   5.873 ± 0.622   ms/op
ClientPb.listUser                         avgt       3   6.946 ± 0.874   ms/op
ClientPb.createUser                     sample  159796   6.002 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.421           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.748           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.199           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.852           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  172712   5.554 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.913           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.979           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.759           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  162751   5.896 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.875           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.047           ms/op
ClientPb.listUser                       sample  140242   6.843 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.166           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.537           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.265           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.879           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.906           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.628           ms/op
