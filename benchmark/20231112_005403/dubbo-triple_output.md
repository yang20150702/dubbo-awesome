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
# Warmup Iteration   1: 1.480 ops/ms
# Warmup Iteration   2: 3.098 ops/ms
# Warmup Iteration   3: 6.077 ops/ms
Iteration   1: 6.960 ops/ms
Iteration   2: 7.087 ops/ms
Iteration   3: 7.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.213 ±(99.9%) 6.098 ops/ms [Average]
  (min, avg, max) = (6.960, 7.213, 7.592), stdev = 0.334
  CI (99.9%): [1.115, 13.311] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 6.197 ops/ms
# Warmup Iteration   3: 7.086 ops/ms
Iteration   1: 7.726 ops/ms
Iteration   2: 7.397 ops/ms
Iteration   3: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.763 ±(99.9%) 7.055 ops/ms [Average]
  (min, avg, max) = (7.397, 7.763, 8.167), stdev = 0.387
  CI (99.9%): [0.708, 14.819] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.962 ops/ms
# Warmup Iteration   2: 6.006 ops/ms
# Warmup Iteration   3: 7.676 ops/ms
Iteration   1: 7.797 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 7.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.664 ±(99.9%) 3.430 ops/ms [Average]
  (min, avg, max) = (7.449, 7.664, 7.797), stdev = 0.188
  CI (99.9%): [4.234, 11.094] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.945 ops/ms
# Warmup Iteration   2: 4.820 ops/ms
# Warmup Iteration   3: 6.337 ops/ms
Iteration   1: 6.414 ops/ms
Iteration   2: 6.550 ops/ms
Iteration   3: 6.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.527 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (6.414, 6.527, 6.617), stdev = 0.104
  CI (99.9%): [4.637, 8.417] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.274 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.008 ms/op
Iteration   1: 4.201 ±(99.9%) 0.009 ms/op
Iteration   2: 4.454 ±(99.9%) 0.007 ms/op
Iteration   3: 4.225 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.293 ±(99.9%) 2.546 ms/op [Average]
  (min, avg, max) = (4.201, 4.293, 4.454), stdev = 0.140
  CI (99.9%): [1.747, 6.839] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.262 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.005 ms/op
Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
Iteration   2: 3.957 ±(99.9%) 0.003 ms/op
Iteration   3: 4.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.013 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.957, 4.013, 4.063), stdev = 0.053
  CI (99.9%): [3.039, 4.986] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.879 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.983 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.006 ms/op
Iteration   1: 4.380 ±(99.9%) 0.004 ms/op
Iteration   2: 4.139 ±(99.9%) 0.006 ms/op
Iteration   3: 4.222 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.247 ±(99.9%) 2.231 ms/op [Average]
  (min, avg, max) = (4.139, 4.247, 4.380), stdev = 0.122
  CI (99.9%): [2.016, 6.478] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.262 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.776 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.202 ±(99.9%) 0.009 ms/op
Iteration   1: 5.296 ±(99.9%) 0.010 ms/op
Iteration   2: 5.289 ±(99.9%) 0.011 ms/op
Iteration   3: 5.168 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.251 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (5.168, 5.251, 5.296), stdev = 0.072
  CI (99.9%): [3.938, 6.564] (assumes normal distribution)


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
# Warmup Iteration   1: 13.403 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.053 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.278 ±(99.9%) 0.032 ms/op
Iteration   1: 4.530 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   4.166 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.650 ms/op
                 createUser·p0.999:  25.222 ms/op
                 createUser·p0.9999: 31.355 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   2: 4.477 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   6.431 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  15.541 ms/op
                 createUser·p0.9999: 27.193 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 4.289 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  14.555 ms/op
                 createUser·p0.9999: 32.767 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 216726
  mean =      4.429 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 168 
    [ 2.500,  5.000) = 184291 
    [ 5.000,  7.500) = 26543 
    [ 7.500, 10.000) = 4093 
    [10.000, 12.500) = 1057 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     22.586 ms/op
     p(99.9900) =     31.905 ms/op
     p(99.9990) =     33.298 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 12.944 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.016 ms/op
Iteration   1: 4.053 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 26.087 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 4.314 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   4.006 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  15.172 ms/op
                 existUser·p0.9999: 32.744 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 4.160 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.961 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  15.818 ms/op
                 existUser·p0.9999: 31.566 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 229990
  mean =      4.173 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 208646 
    [ 5.000,  7.500) = 16348 
    [ 7.500, 10.000) = 3596 
    [10.000, 12.500) = 644 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     33.414 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 14.362 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.504 ±(99.9%) 0.018 ms/op
Iteration   1: 4.175 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   6.250 ms/op
                 getUser·p0.99:   9.471 ms/op
                 getUser·p0.999:  14.865 ms/op
                 getUser·p0.9999: 28.246 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   2: 4.306 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   9.083 ms/op
                 getUser·p0.999:  17.874 ms/op
                 getUser·p0.9999: 30.446 ms/op
                 getUser·p1.00:   30.966 ms/op

Iteration   3: 4.186 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   8.128 ms/op
                 getUser·p0.999:  28.463 ms/op
                 getUser·p0.9999: 32.747 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227331
  mean =      4.222 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 209118 
    [ 5.000,  7.500) = 13143 
    [ 7.500, 10.000) = 3767 
    [10.000, 12.500) = 773 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.852 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     31.728 ms/op
     p(99.9990) =     33.078 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 16.449 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.849 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.021 ms/op
Iteration   1: 4.938 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  21.086 ms/op
                 listUser·p0.9999: 23.105 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 4.858 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  19.224 ms/op
                 listUser·p0.9999: 23.816 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.982 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  16.710 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194945
  mean =      4.925 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 140530 
    [ 5.000,  7.500) = 48925 
    [ 7.500, 10.000) = 3987 
    [10.000, 12.500) = 687 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     18.778 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.217 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.213 ± 6.098  ops/ms
ClientPb.existUser                       thrpt       3   7.763 ± 7.055  ops/ms
ClientPb.getUser                         thrpt       3   7.664 ± 3.430  ops/ms
ClientPb.listUser                        thrpt       3   6.527 ± 1.890  ops/ms
ClientPb.createUser                       avgt       3   4.293 ± 2.546   ms/op
ClientPb.existUser                        avgt       3   4.013 ± 0.974   ms/op
ClientPb.getUser                          avgt       3   4.247 ± 2.231   ms/op
ClientPb.listUser                         avgt       3   5.251 ± 1.313   ms/op
ClientPb.createUser                     sample  216726   4.429 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.589           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.404           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.586           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.905           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  229990   4.173 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.716           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.172           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  227331   4.222 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.852           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.995           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.728           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  194945   4.925 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.365           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
