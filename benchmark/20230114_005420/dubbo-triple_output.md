# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.956 ops/ms
# Warmup Iteration   2: 2.330 ops/ms
# Warmup Iteration   3: 5.005 ops/ms
Iteration   1: 5.040 ops/ms
Iteration   2: 5.202 ops/ms
Iteration   3: 5.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.205 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (5.040, 5.205, 5.374), stdev = 0.167
  CI (99.9%): [2.157, 8.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.466 ops/ms
# Warmup Iteration   2: 4.234 ops/ms
# Warmup Iteration   3: 5.334 ops/ms
Iteration   1: 5.424 ops/ms
Iteration   2: 5.466 ops/ms
Iteration   3: 5.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.479 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (5.424, 5.479, 5.545), stdev = 0.061
  CI (99.9%): [4.364, 6.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.511 ops/ms
# Warmup Iteration   2: 4.472 ops/ms
# Warmup Iteration   3: 5.300 ops/ms
Iteration   1: 5.270 ops/ms
Iteration   2: 5.452 ops/ms
Iteration   3: 5.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.386 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (5.270, 5.386, 5.452), stdev = 0.101
  CI (99.9%): [3.543, 7.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.280 ops/ms
# Warmup Iteration   2: 3.501 ops/ms
# Warmup Iteration   3: 4.524 ops/ms
Iteration   1: 4.553 ops/ms
Iteration   2: 4.633 ops/ms
Iteration   3: 4.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.582 ±(99.9%) 0.810 ops/ms [Average]
  (min, avg, max) = (4.553, 4.582, 4.633), stdev = 0.044
  CI (99.9%): [3.772, 5.392] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.793 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.852 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.232 ±(99.9%) 0.010 ms/op
Iteration   1: 6.297 ±(99.9%) 0.017 ms/op
Iteration   2: 5.929 ±(99.9%) 0.023 ms/op
Iteration   3: 6.157 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.128 ±(99.9%) 3.385 ms/op [Average]
  (min, avg, max) = (5.929, 6.128, 6.297), stdev = 0.186
  CI (99.9%): [2.743, 9.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 21.659 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 7.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.138 ±(99.9%) 0.014 ms/op
Iteration   1: 5.923 ±(99.9%) 0.007 ms/op
Iteration   2: 6.032 ±(99.9%) 0.011 ms/op
Iteration   3: 5.889 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.948 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (5.889, 5.948, 6.032), stdev = 0.075
  CI (99.9%): [4.585, 7.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.544 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 7.695 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.198 ±(99.9%) 0.009 ms/op
Iteration   1: 6.310 ±(99.9%) 0.011 ms/op
Iteration   2: 6.141 ±(99.9%) 0.016 ms/op
Iteration   3: 6.091 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.181 ±(99.9%) 2.095 ms/op [Average]
  (min, avg, max) = (6.091, 6.181, 6.310), stdev = 0.115
  CI (99.9%): [4.086, 8.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 23.665 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 9.495 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 7.263 ±(99.9%) 0.018 ms/op
Iteration   1: 7.135 ±(99.9%) 0.024 ms/op
Iteration   2: 6.886 ±(99.9%) 0.022 ms/op
Iteration   3: 6.838 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.953 ±(99.9%) 2.910 ms/op [Average]
  (min, avg, max) = (6.838, 6.953, 7.135), stdev = 0.159
  CI (99.9%): [4.044, 9.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.949 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 8.189 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.445 ±(99.9%) 0.029 ms/op
Iteration   1: 6.119 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.849 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.323 ms/op
                 createUser·p0.99:   11.425 ms/op
                 createUser·p0.999:  27.835 ms/op
                 createUser·p0.9999: 31.442 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   2: 5.747 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   8.307 ms/op
                 createUser·p0.99:   12.567 ms/op
                 createUser·p0.999:  26.132 ms/op
                 createUser·p0.9999: 29.047 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 5.860 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   13.238 ms/op
                 createUser·p0.999:  31.313 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162459
  mean =      5.905 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 44042 
    [ 5.000,  7.500) = 104419 
    [ 7.500, 10.000) = 10130 
    [10.000, 12.500) = 2172 
    [12.500, 15.000) = 1012 
    [15.000, 17.500) = 317 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     12.567 ms/op
     p(99.9000) =     27.051 ms/op
     p(99.9900) =     34.178 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.681 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 7.556 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.055 ±(99.9%) 0.024 ms/op
Iteration   1: 5.893 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   5.538 ms/op
                 existUser·p0.90:   7.447 ms/op
                 existUser·p0.95:   8.651 ms/op
                 existUser·p0.99:   11.649 ms/op
                 existUser·p0.999:  21.339 ms/op
                 existUser·p0.9999: 29.697 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 5.977 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.458 ms/op
                 existUser·p0.50:   5.587 ms/op
                 existUser·p0.90:   7.643 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   12.548 ms/op
                 existUser·p0.999:  24.607 ms/op
                 existUser·p0.9999: 28.759 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   3: 5.963 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.511 ms/op
                 existUser·p0.50:   5.612 ms/op
                 existUser·p0.90:   7.569 ms/op
                 existUser·p0.95:   8.749 ms/op
                 existUser·p0.99:   12.288 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 26.958 ms/op
                 existUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 161503
  mean =      5.944 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 43024 
    [ 5.000,  7.500) = 101731 
    [ 7.500, 10.000) = 12469 
    [10.000, 12.500) = 2914 
    [12.500, 15.000) = 911 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     23.052 ms/op
     p(99.9900) =     28.934 ms/op
     p(99.9990) =     30.978 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.450 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.351 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.307 ±(99.9%) 0.025 ms/op
Iteration   1: 6.291 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.941 ms/op
                 getUser·p0.50:   5.906 ms/op
                 getUser·p0.90:   8.069 ms/op
                 getUser·p0.95:   8.978 ms/op
                 getUser·p0.99:   12.514 ms/op
                 getUser·p0.999:  24.123 ms/op
                 getUser·p0.9999: 26.900 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 6.072 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   5.718 ms/op
                 getUser·p0.90:   7.569 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   12.796 ms/op
                 getUser·p0.999:  28.337 ms/op
                 getUser·p0.9999: 33.600 ms/op
                 getUser·p1.00:   37.749 ms/op

Iteration   3: 6.228 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.734 ms/op
                 getUser·p0.90:   8.454 ms/op
                 getUser·p0.95:   10.043 ms/op
                 getUser·p0.99:   13.435 ms/op
                 getUser·p0.999:  18.077 ms/op
                 getUser·p0.9999: 49.143 ms/op
                 getUser·p1.00:   50.397 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 154767
  mean =      6.196 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 30236 
    [ 5.000, 10.000) = 119051 
    [10.000, 15.000) = 4884 
    [15.000, 20.000) = 420 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 67 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      8.012 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.943 ms/op
     p(99.9000) =     24.001 ms/op
     p(99.9900) =     37.717 ms/op
     p(99.9990) =     49.931 ms/op
     p(99.9999) =     50.397 ms/op
    p(100.0000) =     50.397 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 25.254 ±(99.9%) 0.414 ms/op
# Warmup Iteration   2: 9.640 ±(99.9%) 0.088 ms/op
# Warmup Iteration   3: 7.445 ±(99.9%) 0.036 ms/op
Iteration   1: 7.022 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.631 ms/op
                 listUser·p0.999:  26.686 ms/op
                 listUser·p0.9999: 31.140 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 6.982 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   6.603 ms/op
                 listUser·p0.90:   8.765 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   13.926 ms/op
                 listUser·p0.999:  29.020 ms/op
                 listUser·p0.9999: 33.358 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 6.996 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   6.644 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.681 ms/op
                 listUser·p0.999:  30.434 ms/op
                 listUser·p0.9999: 34.238 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137219
  mean =      7.000 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 2258 
    [ 5.000,  7.500) = 102894 
    [ 7.500, 10.000) = 24703 
    [10.000, 12.500) = 4883 
    [12.500, 15.000) = 1677 
    [15.000, 17.500) = 404 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      6.644 ms/op
     p(90.0000) =      8.749 ms/op
     p(95.0000) =     10.125 ms/op
     p(99.0000) =     13.776 ms/op
     p(99.9000) =     28.337 ms/op
     p(99.9900) =     33.806 ms/op
     p(99.9990) =     34.702 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.205 ± 3.048  ops/ms
ClientPb.existUser                       thrpt       3   5.479 ± 1.115  ops/ms
ClientPb.getUser                         thrpt       3   5.386 ± 1.844  ops/ms
ClientPb.listUser                        thrpt       3   4.582 ± 0.810  ops/ms
ClientPb.createUser                       avgt       3   6.128 ± 3.385   ms/op
ClientPb.existUser                        avgt       3   5.948 ± 1.363   ms/op
ClientPb.getUser                          avgt       3   6.181 ± 2.095   ms/op
ClientPb.listUser                         avgt       3   6.953 ± 2.910   ms/op
ClientPb.createUser                     sample  162459   5.905 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.356           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.567           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.051           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  161503   5.944 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.438           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.561           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.667           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.108           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.052           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.934           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  154767   6.196 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.012           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.943           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.001           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.717           ms/op
ClientPb.getUser:getUser·p1.00          sample          50.397           ms/op
ClientPb.listUser                       sample  137219   7.000 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.225           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.125           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.776           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.337           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.806           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
