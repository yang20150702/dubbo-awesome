# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.963 ops/ms
# Warmup Iteration   2: 2.282 ops/ms
# Warmup Iteration   3: 5.426 ops/ms
Iteration   1: 5.853 ops/ms
Iteration   2: 5.961 ops/ms
Iteration   3: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.818 ±(99.9%) 2.962 ops/ms [Average]
  (min, avg, max) = (5.641, 5.818, 5.961), stdev = 0.162
  CI (99.9%): [2.856, 8.781] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.540 ops/ms
# Warmup Iteration   2: 4.209 ops/ms
# Warmup Iteration   3: 5.584 ops/ms
Iteration   1: 5.588 ops/ms
Iteration   2: 5.930 ops/ms
Iteration   3: 6.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.930 ±(99.9%) 6.237 ops/ms [Average]
  (min, avg, max) = (5.588, 5.930, 6.272), stdev = 0.342
  CI (99.9%): [≈ 0, 12.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.328 ops/ms
# Warmup Iteration   2: 4.134 ops/ms
# Warmup Iteration   3: 5.690 ops/ms
Iteration   1: 5.701 ops/ms
Iteration   2: 5.599 ops/ms
Iteration   3: 5.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.752 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (5.599, 5.752, 5.956), stdev = 0.184
  CI (99.9%): [2.402, 9.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.730 ops/ms
# Warmup Iteration   2: 4.307 ops/ms
# Warmup Iteration   3: 5.238 ops/ms
Iteration   1: 5.125 ops/ms
Iteration   2: 5.071 ops/ms
Iteration   3: 5.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.141 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (5.071, 5.141, 5.226), stdev = 0.079
  CI (99.9%): [3.702, 6.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.756 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.511 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.564 ±(99.9%) 0.012 ms/op
Iteration   1: 5.263 ±(99.9%) 0.012 ms/op
Iteration   2: 5.325 ±(99.9%) 0.014 ms/op
Iteration   3: 5.199 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.262 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (5.199, 5.262, 5.325), stdev = 0.063
  CI (99.9%): [4.113, 6.412] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.954 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.612 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.953 ±(99.9%) 0.008 ms/op
Iteration   1: 5.121 ±(99.9%) 0.007 ms/op
Iteration   2: 4.989 ±(99.9%) 0.005 ms/op
Iteration   3: 4.892 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.000 ±(99.9%) 2.093 ms/op [Average]
  (min, avg, max) = (4.892, 5.000, 5.121), stdev = 0.115
  CI (99.9%): [2.908, 7.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.391 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.005 ms/op
Iteration   1: 5.452 ±(99.9%) 0.005 ms/op
Iteration   2: 5.227 ±(99.9%) 0.010 ms/op
Iteration   3: 5.348 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.343 ±(99.9%) 2.052 ms/op [Average]
  (min, avg, max) = (5.227, 5.343, 5.452), stdev = 0.112
  CI (99.9%): [3.290, 7.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.867 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 7.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.276 ±(99.9%) 0.012 ms/op
Iteration   1: 6.385 ±(99.9%) 0.009 ms/op
Iteration   2: 6.169 ±(99.9%) 0.009 ms/op
Iteration   3: 5.942 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.165 ±(99.9%) 4.040 ms/op [Average]
  (min, avg, max) = (5.942, 6.165, 6.385), stdev = 0.221
  CI (99.9%): [2.126, 10.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.718 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 6.546 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.810 ±(99.9%) 0.024 ms/op
Iteration   1: 5.269 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.110 ms/op
                 createUser·p0.99:   9.670 ms/op
                 createUser·p0.999:  26.903 ms/op
                 createUser·p0.9999: 32.593 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   2: 5.473 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.086 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  25.477 ms/op
                 createUser·p0.9999: 29.829 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 5.595 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.445 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 30.754 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176423
  mean =      5.442 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 72313 
    [ 5.000,  7.500) = 96732 
    [ 7.500, 10.000) = 5617 
    [10.000, 12.500) = 1004 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     33.065 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.819 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.073 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.255 ±(99.9%) 0.017 ms/op
Iteration   1: 5.300 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.570 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   9.110 ms/op
                 existUser·p0.999:  23.912 ms/op
                 existUser·p0.9999: 27.716 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   2: 5.273 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   10.470 ms/op
                 existUser·p0.999:  16.612 ms/op
                 existUser·p0.9999: 26.540 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   3: 5.440 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.171 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   11.908 ms/op
                 existUser·p0.999:  27.429 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179779
  mean =      5.337 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 93850 
    [ 5.000,  7.500) = 77520 
    [ 7.500, 10.000) = 6205 
    [10.000, 12.500) = 1253 
    [12.500, 15.000) = 545 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.389 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     32.413 ms/op
     p(99.9990) =     34.277 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.780 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 7.350 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.631 ±(99.9%) 0.020 ms/op
Iteration   1: 5.624 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   7.913 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  19.759 ms/op
                 getUser·p0.9999: 32.024 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   2: 5.903 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.840 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   13.305 ms/op
                 getUser·p0.999:  25.192 ms/op
                 getUser·p0.9999: 29.286 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 5.949 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.482 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   7.389 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  28.705 ms/op
                 getUser·p0.9999: 32.086 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164819
  mean =      5.822 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 44436 
    [ 5.000,  7.500) = 105731 
    [ 7.500, 10.000) = 10962 
    [10.000, 12.500) = 2278 
    [12.500, 15.000) = 774 
    [15.000, 17.500) = 270 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     21.305 ms/op
     p(99.9900) =     31.719 ms/op
     p(99.9990) =     33.951 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 24.075 ±(99.9%) 0.482 ms/op
# Warmup Iteration   2: 9.520 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.459 ±(99.9%) 0.026 ms/op
Iteration   1: 6.230 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.002 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  25.187 ms/op
                 listUser·p0.9999: 43.441 ms/op
                 listUser·p1.00:   43.975 ms/op

Iteration   2: 6.427 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.822 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   13.819 ms/op
                 listUser·p0.999:  29.638 ms/op
                 listUser·p0.9999: 32.608 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   3: 6.127 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  24.828 ms/op
                 listUser·p0.9999: 32.732 ms/op
                 listUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153335
  mean =      6.259 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6591 
    [ 5.000, 10.000) = 142545 
    [10.000, 15.000) = 3589 
    [15.000, 20.000) = 257 
    [20.000, 25.000) = 134 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     28.377 ms/op
     p(99.9900) =     43.166 ms/op
     p(99.9990) =     43.870 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.818 ± 2.962  ops/ms
ClientPb.existUser                       thrpt       3   5.930 ± 6.237  ops/ms
ClientPb.getUser                         thrpt       3   5.752 ± 3.350  ops/ms
ClientPb.listUser                        thrpt       3   5.141 ± 1.439  ops/ms
ClientPb.createUser                       avgt       3   5.262 ± 1.149   ms/op
ClientPb.existUser                        avgt       3   5.000 ± 2.093   ms/op
ClientPb.getUser                          avgt       3   5.343 ± 2.052   ms/op
ClientPb.listUser                         avgt       3   6.165 ± 4.040   ms/op
ClientPb.createUser                     sample  176423   5.442 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.961           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.054           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  179779   5.337 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.389           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.453           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.137           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.413           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.062           ms/op
ClientPb.getUser                        sample  164819   5.822 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.575           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.274           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.719           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  153335   6.259 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.298           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.288           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.166           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.975           ms/op
