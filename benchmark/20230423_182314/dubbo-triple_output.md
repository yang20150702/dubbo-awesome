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
# Warmup Iteration   1: 2.164 ops/ms
# Warmup Iteration   2: 5.280 ops/ms
# Warmup Iteration   3: 8.413 ops/ms
Iteration   1: 9.285 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.324 ±(99.9%) 3.679 ops/ms [Average]
  (min, avg, max) = (9.144, 9.324, 9.542), stdev = 0.202
  CI (99.9%): [5.645, 13.002] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 10.011 ops/ms
Iteration   2: 9.281 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.740 ±(99.9%) 7.282 ops/ms [Average]
  (min, avg, max) = (9.281, 9.740, 10.011), stdev = 0.399
  CI (99.9%): [2.458, 17.021] (assumes normal distribution)


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
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.383 ops/ms
Iteration   2: 9.163 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.324 ±(99.9%) 2.581 ops/ms [Average]
  (min, avg, max) = (9.163, 9.324, 9.427), stdev = 0.141
  CI (99.9%): [6.743, 11.906] (assumes normal distribution)


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
# Warmup Iteration   1: 2.690 ops/ms
# Warmup Iteration   2: 7.294 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.051 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.086 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (8.051, 8.086, 8.110), stdev = 0.031
  CI (99.9%): [7.517, 8.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.984 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.011 ms/op
Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
Iteration   3: 3.431 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.350, 3.393, 3.431), stdev = 0.041
  CI (99.9%): [2.651, 4.134] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.156 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.005 ms/op
Iteration   1: 3.240 ±(99.9%) 0.005 ms/op
Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
Iteration   3: 3.308 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.266 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (3.240, 3.266, 3.308), stdev = 0.036
  CI (99.9%): [2.606, 3.927] (assumes normal distribution)


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
# Warmup Iteration   1: 9.772 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.012 ms/op
Iteration   1: 3.447 ±(99.9%) 0.005 ms/op
Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
Iteration   3: 3.322 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.322, 3.378, 3.447), stdev = 0.064
  CI (99.9%): [2.214, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 11.173 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.007 ms/op
Iteration   1: 4.054 ±(99.9%) 0.008 ms/op
Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
Iteration   3: 3.978 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.001 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.971, 4.001, 4.054), stdev = 0.046
  CI (99.9%): [3.168, 4.834] (assumes normal distribution)


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.457 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  22.397 ms/op
                 createUser·p0.9999: 26.730 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.396 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  22.960 ms/op
                 createUser·p0.9999: 40.933 ms/op
                 createUser·p1.00:   43.975 ms/op

Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  20.045 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281787
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 275570 
    [ 5.000, 10.000) = 5591 
    [10.000, 15.000) = 306 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     39.364 ms/op
     p(99.9990) =     43.617 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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
# Warmup Iteration   1: 9.585 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.378 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  22.173 ms/op
                 existUser·p0.9999: 26.035 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.396 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 25.255 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288123
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20530 
    [ 2.500,  5.000) = 261834 
    [ 5.000,  7.500) = 5068 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.252 ms/op
     p(99.9900) =     25.303 ms/op
     p(99.9990) =     26.353 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 7.960 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
Iteration   1: 3.454 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.618 ms/op
                 getUser·p0.999:  18.252 ms/op
                 getUser·p0.9999: 21.159 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  19.483 ms/op
                 getUser·p0.9999: 27.923 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.034 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  18.978 ms/op
                 getUser·p0.9999: 25.614 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279711
  mean =      3.433 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4481 
    [ 2.500,  5.000) = 267629 
    [ 5.000,  7.500) = 6620 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     18.444 ms/op
     p(99.9900) =     26.546 ms/op
     p(99.9990) =     29.958 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 10.445 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.016 ms/op
Iteration   1: 3.955 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  21.083 ms/op
                 listUser·p0.9999: 27.643 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.155 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 20.547 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240535
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 231097 
    [ 5.000,  7.500) = 7126 
    [ 7.500, 10.000) = 1491 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     16.366 ms/op
     p(99.9900) =     27.163 ms/op
     p(99.9990) =     28.263 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.324 ± 3.679  ops/ms
ClientPb.existUser                       thrpt       3   9.740 ± 7.282  ops/ms
ClientPb.getUser                         thrpt       3   9.324 ± 2.581  ops/ms
ClientPb.listUser                        thrpt       3   8.086 ± 0.568  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 0.742   ms/op
ClientPb.existUser                        avgt       3   3.266 ± 0.660   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 1.164   ms/op
ClientPb.listUser                         avgt       3   4.001 ± 0.833   ms/op
ClientPb.createUser                     sample  281787   3.405 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.260           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.349           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.364           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.975           ms/op
ClientPb.existUser                      sample  288123   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.565           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.252           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.303           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  279711   3.433 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.444           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.546           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  240535   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.366           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.163           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.541           ms/op
