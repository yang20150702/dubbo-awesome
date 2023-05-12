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
# Warmup Iteration   1: 1.165 ops/ms
# Warmup Iteration   2: 2.392 ops/ms
# Warmup Iteration   3: 5.292 ops/ms
Iteration   1: 5.902 ops/ms
Iteration   2: 5.940 ops/ms
Iteration   3: 6.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.986 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (5.902, 5.986, 6.115), stdev = 0.113
  CI (99.9%): [3.918, 8.053] (assumes normal distribution)


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
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 5.302 ops/ms
# Warmup Iteration   3: 6.217 ops/ms
Iteration   1: 6.216 ops/ms
Iteration   2: 6.165 ops/ms
Iteration   3: 6.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.232 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (6.165, 6.232, 6.316), stdev = 0.077
  CI (99.9%): [4.834, 7.630] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.670 ops/ms
# Warmup Iteration   2: 4.819 ops/ms
# Warmup Iteration   3: 5.766 ops/ms
Iteration   1: 5.907 ops/ms
Iteration   2: 6.115 ops/ms
Iteration   3: 6.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.027 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (5.907, 6.027, 6.115), stdev = 0.108
  CI (99.9%): [4.055, 8.000] (assumes normal distribution)


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
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.246 ops/ms
# Warmup Iteration   3: 4.991 ops/ms
Iteration   1: 5.081 ops/ms
Iteration   2: 5.107 ops/ms
Iteration   3: 5.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.114 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (5.081, 5.114, 5.153), stdev = 0.037
  CI (99.9%): [4.447, 5.781] (assumes normal distribution)


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
# Warmup Iteration   1: 17.114 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.653 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.704 ±(99.9%) 0.011 ms/op
Iteration   1: 5.376 ±(99.9%) 0.009 ms/op
Iteration   2: 5.291 ±(99.9%) 0.018 ms/op
Iteration   3: 5.184 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.284 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (5.184, 5.284, 5.376), stdev = 0.096
  CI (99.9%): [3.529, 7.038] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.986 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.048 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.151 ±(99.9%) 0.010 ms/op
Iteration   1: 5.185 ±(99.9%) 0.010 ms/op
Iteration   2: 5.115 ±(99.9%) 0.012 ms/op
Iteration   3: 5.146 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.149 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (5.115, 5.149, 5.185), stdev = 0.035
  CI (99.9%): [4.510, 5.787] (assumes normal distribution)


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
# Warmup Iteration   1: 16.229 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.412 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.009 ms/op
Iteration   1: 5.156 ±(99.9%) 0.018 ms/op
Iteration   2: 5.208 ±(99.9%) 0.015 ms/op
Iteration   3: 5.128 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.164 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (5.128, 5.164, 5.208), stdev = 0.041
  CI (99.9%): [4.420, 5.909] (assumes normal distribution)


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
# Warmup Iteration   1: 19.867 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.678 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.452 ±(99.9%) 0.011 ms/op
Iteration   1: 6.161 ±(99.9%) 0.016 ms/op
Iteration   2: 6.119 ±(99.9%) 0.011 ms/op
Iteration   3: 6.037 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.106 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (6.037, 6.106, 6.161), stdev = 0.063
  CI (99.9%): [4.957, 7.255] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.292 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.994 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.873 ±(99.9%) 0.029 ms/op
Iteration   1: 5.440 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  25.992 ms/op
                 createUser·p0.9999: 30.740 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   2: 5.411 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  26.037 ms/op
                 createUser·p0.9999: 34.084 ms/op
                 createUser·p1.00:   35.127 ms/op

Iteration   3: 5.339 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.528 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  28.450 ms/op
                 createUser·p0.9999: 31.236 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177886
  mean =      5.396 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 79026 
    [ 5.000,  7.500) = 88532 
    [ 7.500, 10.000) = 8332 
    [10.000, 12.500) = 1325 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     33.496 ms/op
     p(99.9990) =     34.566 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 15.732 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 5.919 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.252 ±(99.9%) 0.017 ms/op
Iteration   1: 4.944 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  15.205 ms/op
                 existUser·p0.9999: 26.464 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   2: 5.227 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.332 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  22.446 ms/op
                 existUser·p0.9999: 27.324 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 5.129 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.080 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  16.771 ms/op
                 existUser·p0.9999: 32.426 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188277
  mean =      5.098 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 110125 
    [ 5.000,  7.500) = 71490 
    [ 7.500, 10.000) = 5384 
    [10.000, 12.500) = 787 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     30.568 ms/op
     p(99.9990) =     33.441 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 16.547 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.222 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.513 ±(99.9%) 0.019 ms/op
Iteration   1: 5.217 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.843 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.406 ms/op
                 getUser·p0.99:   10.306 ms/op
                 getUser·p0.999:  24.370 ms/op
                 getUser·p0.9999: 27.812 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   2: 5.485 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.109 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  26.749 ms/op
                 getUser·p0.9999: 31.201 ms/op
                 getUser·p1.00:   31.326 ms/op

Iteration   3: 5.237 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  26.049 ms/op
                 getUser·p0.9999: 31.837 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180663
  mean =      5.310 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 89359 
    [ 5.000,  7.500) = 81109 
    [ 7.500, 10.000) = 8070 
    [10.000, 12.500) = 1268 
    [12.500, 15.000) = 443 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     25.090 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     32.541 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 19.251 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.302 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.366 ±(99.9%) 0.023 ms/op
Iteration   1: 6.263 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.968 ms/op
                 listUser·p0.999:  27.296 ms/op
                 listUser·p0.9999: 36.431 ms/op
                 listUser·p1.00:   37.945 ms/op

Iteration   2: 6.298 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.916 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.843 ms/op
                 listUser·p0.999:  28.931 ms/op
                 listUser·p0.9999: 34.723 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   3: 6.429 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  23.808 ms/op
                 listUser·p0.9999: 29.398 ms/op
                 listUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151585
  mean =      6.329 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 8534 
    [ 5.000,  7.500) = 126861 
    [ 7.500, 10.000) = 12866 
    [10.000, 12.500) = 2192 
    [12.500, 15.000) = 602 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.503 ms/op
     p(50.0000) =      6.046 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     27.211 ms/op
     p(99.9900) =     34.789 ms/op
     p(99.9990) =     37.607 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.986 ± 2.068  ops/ms
ClientPb.existUser                       thrpt       3   6.232 ± 1.398  ops/ms
ClientPb.getUser                         thrpt       3   6.027 ± 1.973  ops/ms
ClientPb.listUser                        thrpt       3   5.114 ± 0.667  ops/ms
ClientPb.createUser                       avgt       3   5.284 ± 1.755   ms/op
ClientPb.existUser                        avgt       3   5.149 ± 0.638   ms/op
ClientPb.getUser                          avgt       3   5.164 ± 0.744   ms/op
ClientPb.listUser                         avgt       3   6.106 ± 1.149   ms/op
ClientPb.createUser                     sample  177886   5.396 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.644           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.766           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.247           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.496           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.127           ms/op
ClientPb.existUser                      sample  188277   5.098 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.201           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.322           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.777           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.568           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  180663   5.310 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.109           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  151585   6.329 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.764           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.211           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.789           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.945           ms/op
