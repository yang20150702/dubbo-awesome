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
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 5.677 ops/ms
# Warmup Iteration   3: 9.372 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 9.850 ops/ms
Iteration   3: 9.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.845 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (9.802, 9.845, 9.883), stdev = 0.041
  CI (99.9%): [9.101, 10.589] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.858 ops/ms
# Warmup Iteration   2: 9.454 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.276 ops/ms
Iteration   2: 10.234 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.266 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (10.234, 10.266, 10.289), stdev = 0.029
  CI (99.9%): [9.738, 10.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 8.997 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 9.942 ops/ms
Iteration   2: 10.194 ops/ms
Iteration   3: 9.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.033 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (9.942, 10.033, 10.194), stdev = 0.140
  CI (99.9%): [7.474, 12.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.966 ops/ms
# Warmup Iteration   2: 7.218 ops/ms
# Warmup Iteration   3: 8.049 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.393 ±(99.9%) 3.081 ops/ms [Average]
  (min, avg, max) = (8.222, 8.393, 8.560), stdev = 0.169
  CI (99.9%): [5.312, 11.474] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.819 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.002 ms/op
Iteration   1: 3.256 ±(99.9%) 0.007 ms/op
Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
Iteration   3: 3.272 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.255 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.237, 3.255, 3.272), stdev = 0.018
  CI (99.9%): [2.934, 3.576] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.766 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.005 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.125 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.117 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (3.091, 3.117, 3.134), stdev = 0.023
  CI (99.9%): [2.705, 3.528] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.472 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.002 ms/op
Iteration   1: 3.234 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.122, 3.175, 3.234), stdev = 0.056
  CI (99.9%): [2.145, 4.206] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.915 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.004 ms/op
Iteration   1: 3.878 ±(99.9%) 0.007 ms/op
Iteration   2: 3.792 ±(99.9%) 0.005 ms/op
Iteration   3: 3.763 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.811 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.763, 3.811, 3.878), stdev = 0.060
  CI (99.9%): [2.717, 4.905] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.925 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  17.375 ms/op
                 createUser·p0.9999: 20.040 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.293 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  20.905 ms/op
                 createUser·p0.9999: 24.642 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  15.935 ms/op
                 createUser·p0.9999: 30.554 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289857
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14960 
    [ 2.500,  5.000) = 270177 
    [ 5.000,  7.500) = 3739 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     17.011 ms/op
     p(99.9900) =     30.311 ms/op
     p(99.9990) =     31.943 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 8.070 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  16.738 ms/op
                 existUser·p0.9999: 20.973 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301239
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20693 
    [ 2.500,  5.000) = 275802 
    [ 5.000,  7.500) = 4100 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     24.608 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 8.507 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  17.046 ms/op
                 getUser·p0.9999: 19.178 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  17.848 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.425 ms/op
                 getUser·p0.9999: 20.660 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295477
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7594 
    [ 2.500,  5.000) = 280379 
    [ 5.000,  7.500) = 6412 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.786 ms/op
     p(99.9900) =     20.560 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 8.883 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.826 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  16.054 ms/op
                 listUser·p0.9999: 20.196 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.821 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.164 ms/op
                 listUser·p0.999:  14.374 ms/op
                 listUser·p0.9999: 17.552 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 16.914 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251410
  mean =      3.815 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 245519 
    [ 5.000,  7.500) = 4234 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.165 ms/op
     p(99.9900) =     19.099 ms/op
     p(99.9990) =     21.315 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.845 ± 0.744  ops/ms
ClientPb.existUser                       thrpt       3  10.266 ± 0.529  ops/ms
ClientPb.getUser                         thrpt       3  10.033 ± 2.559  ops/ms
ClientPb.listUser                        thrpt       3   8.393 ± 3.081  ops/ms
ClientPb.createUser                       avgt       3   3.255 ± 0.321   ms/op
ClientPb.existUser                        avgt       3   3.117 ± 0.412   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 1.030   ms/op
ClientPb.listUser                         avgt       3   3.811 ± 1.094   ms/op
ClientPb.createUser                     sample  289857   3.309 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.311           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  301239   3.187 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.399           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  295477   3.248 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.786           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.741           ms/op
ClientPb.listUser                       sample  251410   3.815 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.165           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.099           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.398           ms/op
