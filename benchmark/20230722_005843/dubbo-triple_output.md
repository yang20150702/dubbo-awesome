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
# Warmup Iteration   1: 2.019 ops/ms
# Warmup Iteration   2: 6.202 ops/ms
# Warmup Iteration   3: 8.742 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.080 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.188 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (9.080, 9.188, 9.299), stdev = 0.110
  CI (99.9%): [7.187, 11.189] (assumes normal distribution)


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
# Warmup Iteration   1: 2.901 ops/ms
# Warmup Iteration   2: 8.322 ops/ms
# Warmup Iteration   3: 9.237 ops/ms
Iteration   1: 9.658 ops/ms
Iteration   2: 9.458 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.677 ±(99.9%) 4.182 ops/ms [Average]
  (min, avg, max) = (9.458, 9.677, 9.915), stdev = 0.229
  CI (99.9%): [5.495, 13.859] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.189 ops/ms
# Warmup Iteration   2: 8.554 ops/ms
# Warmup Iteration   3: 8.933 ops/ms
Iteration   1: 8.648 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.035 ±(99.9%) 6.129 ops/ms [Average]
  (min, avg, max) = (8.648, 9.035, 9.249), stdev = 0.336
  CI (99.9%): [2.906, 15.164] (assumes normal distribution)


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
# Warmup Iteration   1: 2.732 ops/ms
# Warmup Iteration   2: 7.140 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 8.011 ops/ms
Iteration   3: 7.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.839 ±(99.9%) 2.744 ops/ms [Average]
  (min, avg, max) = (7.728, 7.839, 8.011), stdev = 0.150
  CI (99.9%): [5.095, 10.584] (assumes normal distribution)


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
# Warmup Iteration   1: 9.913 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.005 ms/op
Iteration   1: 3.518 ±(99.9%) 0.009 ms/op
Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
Iteration   3: 3.359 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.359, 3.419, 3.518), stdev = 0.087
  CI (99.9%): [1.840, 4.998] (assumes normal distribution)


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
# Warmup Iteration   1: 9.064 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.005 ms/op
Iteration   1: 3.421 ±(99.9%) 0.004 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.318 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.362 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.318, 3.362, 3.421), stdev = 0.053
  CI (99.9%): [2.391, 4.333] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.189 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.005 ms/op
Iteration   1: 3.571 ±(99.9%) 0.008 ms/op
Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
Iteration   3: 3.450 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.499 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.450, 3.499, 3.571), stdev = 0.064
  CI (99.9%): [2.338, 4.659] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.771 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.486 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.008 ms/op
Iteration   1: 4.069 ±(99.9%) 0.008 ms/op
Iteration   2: 4.051 ±(99.9%) 0.008 ms/op
Iteration   3: 4.029 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.050 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (4.029, 4.050, 4.069), stdev = 0.020
  CI (99.9%): [3.680, 4.420] (assumes normal distribution)


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
# Warmup Iteration   1: 9.943 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.011 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  20.532 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.802 ms/op
                 createUser·p0.999:  23.399 ms/op
                 createUser·p0.9999: 30.533 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 3.369 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  16.391 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283334
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8945 
    [ 2.500,  5.000) = 270173 
    [ 5.000,  7.500) = 3447 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.011 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.559 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     31.146 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 9.979 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.363 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  20.082 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.501 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  23.298 ms/op
                 existUser·p0.9999: 31.616 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  10.371 ms/op
                 existUser·p0.9999: 27.211 ms/op
                 existUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281792
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10742 
    [ 2.500,  5.000) = 264661 
    [ 5.000,  7.500) = 5390 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.210 ms/op
     p(99.9900) =     30.114 ms/op
     p(99.9990) =     31.961 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.299 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.010 ms/op
Iteration   1: 3.569 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  22.362 ms/op
                 getUser·p0.9999: 35.062 ms/op
                 getUser·p1.00:   35.783 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  22.950 ms/op
                 getUser·p0.9999: 28.068 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.590 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  17.644 ms/op
                 getUser·p0.9999: 24.631 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273071
  mean =      3.514 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 534 
    [ 2.500,  5.000) = 264429 
    [ 5.000,  7.500) = 6579 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     18.315 ms/op
     p(99.9900) =     32.965 ms/op
     p(99.9990) =     35.556 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 12.488 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.015 ms/op
Iteration   1: 4.164 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  19.379 ms/op
                 listUser·p0.9999: 26.727 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   2: 4.204 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.050 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  15.782 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 4.070 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 16.767 ms/op
                 listUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231623
  mean =      4.145 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 220229 
    [ 5.000,  7.500) = 8522 
    [ 7.500, 10.000) = 1793 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 272 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.821 ms/op
     p(99.9000) =     16.128 ms/op
     p(99.9900) =     25.357 ms/op
     p(99.9990) =     29.791 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.188 ± 2.001  ops/ms
ClientPb.existUser                       thrpt       3   9.677 ± 4.182  ops/ms
ClientPb.getUser                         thrpt       3   9.035 ± 6.129  ops/ms
ClientPb.listUser                        thrpt       3   7.839 ± 2.744  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 1.579   ms/op
ClientPb.existUser                        avgt       3   3.362 ± 0.971   ms/op
ClientPb.getUser                          avgt       3   3.499 ± 1.160   ms/op
ClientPb.listUser                         avgt       3   4.050 ± 0.370   ms/op
ClientPb.createUser                     sample  283334   3.388 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.452           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.011           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.559           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.213           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.785           ms/op
ClientPb.existUser                      sample  281792   3.404 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.426           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.210           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.114           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  273071   3.514 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.622           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.965           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  231623   4.145 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.821           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.128           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.357           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.983           ms/op
