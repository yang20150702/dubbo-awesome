# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.873 ops/ms
# Warmup Iteration   2: 12.241 ops/ms
# Warmup Iteration   3: 12.640 ops/ms
Iteration   1: 12.974 ops/ms
Iteration   2: 12.809 ops/ms
Iteration   3: 12.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.909 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (12.809, 12.909, 12.974), stdev = 0.088
  CI (99.9%): [11.312, 14.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.539 ops/ms
# Warmup Iteration   2: 13.100 ops/ms
# Warmup Iteration   3: 13.137 ops/ms
Iteration   1: 13.098 ops/ms
Iteration   2: 13.148 ops/ms
Iteration   3: 13.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.112 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (13.089, 13.112, 13.148), stdev = 0.032
  CI (99.9%): [12.536, 13.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.046 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 12.870 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.957 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (12.870, 12.957, 13.021), stdev = 0.078
  CI (99.9%): [11.531, 14.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.838 ops/ms
# Warmup Iteration   2: 10.784 ops/ms
# Warmup Iteration   3: 10.782 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 10.879 ops/ms
Iteration   3: 10.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.886 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (10.854, 10.886, 10.926), stdev = 0.037
  CI (99.9%): [10.220, 11.552] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.003 ms/op
Iteration   1: 2.441 ±(99.9%) 0.003 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.446 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.441, 2.446, 2.451), stdev = 0.005
  CI (99.9%): [2.355, 2.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.372 ±(99.9%) 0.004 ms/op
Iteration   1: 2.391 ±(99.9%) 0.005 ms/op
Iteration   2: 2.377 ±(99.9%) 0.004 ms/op
Iteration   3: 2.398 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.389 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.377, 2.389, 2.398), stdev = 0.011
  CI (99.9%): [2.196, 2.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.415 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.427 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (2.415, 2.427, 2.440), stdev = 0.013
  CI (99.9%): [2.192, 2.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.005 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
Iteration   2: 2.928 ±(99.9%) 0.005 ms/op
Iteration   3: 2.892 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.913 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.892, 2.913, 2.928), stdev = 0.018
  CI (99.9%): [2.577, 3.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 13.204 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.486 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  6.062 ms/op
                 createUser·p0.9999: 12.777 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.069 ms/op
                 createUser·p0.9999: 10.447 ms/op
                 createUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 393040
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 199371 
    [ 2.500,  3.750) = 189559 
    [ 3.750,  5.000) = 3096 
    [ 5.000,  6.250) = 481 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.813 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.341 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.534 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.343 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.301 ±(99.9%) 0.005 ms/op
Iteration   1: 2.317 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.343 ms/op
                 existUser·p0.90:   2.847 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 12.383 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.298 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.331 ms/op
                 existUser·p0.90:   2.822 ms/op
                 existUser·p0.95:   2.925 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  6.864 ms/op
                 existUser·p0.9999: 11.853 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 2.295 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.310 ms/op
                 existUser·p0.90:   2.818 ms/op
                 existUser·p0.95:   2.925 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  7.222 ms/op
                 existUser·p0.9999: 9.899 ms/op
                 existUser·p1.00:   10.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 416362
  mean =      2.303 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 246755 
    [ 2.500,  3.750) = 167071 
    [ 3.750,  5.000) = 1773 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 132 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.327 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      2.945 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =      6.714 ms/op
     p(99.9900) =     12.157 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.402 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.925 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  6.604 ms/op
                 getUser·p0.9999: 14.420 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  6.718 ms/op
                 getUser·p0.9999: 11.968 ms/op
                 getUser·p1.00:   12.337 ms/op

Iteration   3: 2.398 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  6.586 ms/op
                 getUser·p0.9999: 12.610 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 398171
  mean =      2.409 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 206347 
    [ 2.500,  3.750) = 188390 
    [ 3.750,  5.000) = 2646 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.633 ms/op
     p(99.9900) =     12.881 ms/op
     p(99.9990) =     14.697 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.909 ms/op
                 listUser·p0.9999: 10.282 ms/op
                 listUser·p1.00:   10.600 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.588 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 10.951 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322581
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 98788 
    [ 2.500,  3.750) = 185831 
    [ 3.750,  5.000) = 31162 
    [ 5.000,  6.250) = 5375 
    [ 6.250,  7.500) = 633 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.776 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.909 ± 1.597  ops/ms
ClientPb.existUser                       thrpt       3  13.112 ± 0.575  ops/ms
ClientPb.getUser                         thrpt       3  12.957 ± 1.426  ops/ms
ClientPb.listUser                        thrpt       3  10.886 ± 0.666  ops/ms
ClientPb.createUser                       avgt       3   2.446 ± 0.091   ms/op
ClientPb.existUser                        avgt       3   2.389 ± 0.192   ms/op
ClientPb.getUser                          avgt       3   2.427 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   2.913 ± 0.336   ms/op
ClientPb.createUser                     sample  393040   2.440 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.813           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.829           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.730           ms/op
ClientPb.existUser                      sample  416362   2.303 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.724           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.327           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.157           ms/op
ClientPb.existUser:existUser·p1.00      sample          12.894           ms/op
ClientPb.getUser                        sample  398171   2.409 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.564           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.429           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.937           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.633           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.881           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.925           ms/op
ClientPb.listUser                       sample  322581   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.749           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.173           ms/op
