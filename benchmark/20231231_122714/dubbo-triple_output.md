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
# Warmup Iteration   1: 4.749 ops/ms
# Warmup Iteration   2: 12.195 ops/ms
# Warmup Iteration   3: 12.634 ops/ms
Iteration   1: 12.728 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.843 ±(99.9%) 2.246 ops/ms [Average]
  (min, avg, max) = (12.728, 12.843, 12.973), stdev = 0.123
  CI (99.9%): [10.598, 15.089] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.331 ops/ms
# Warmup Iteration   2: 12.916 ops/ms
# Warmup Iteration   3: 13.083 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.174 ops/ms
Iteration   3: 13.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.194 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (13.174, 13.194, 13.219), stdev = 0.023
  CI (99.9%): [12.779, 13.609] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.875 ops/ms
# Warmup Iteration   2: 12.495 ops/ms
# Warmup Iteration   3: 12.890 ops/ms
Iteration   1: 12.914 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.908 ±(99.9%) 0.193 ops/ms [Average]
  (min, avg, max) = (12.896, 12.908, 12.915), stdev = 0.011
  CI (99.9%): [12.715, 13.101] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.887 ops/ms
# Warmup Iteration   2: 10.635 ops/ms
# Warmup Iteration   3: 10.724 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.717 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (10.653, 10.717, 10.769), stdev = 0.059
  CI (99.9%): [9.642, 11.792] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.484 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.451, 2.484, 2.519), stdev = 0.034
  CI (99.9%): [1.860, 3.109] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.414, 2.422, 2.426), stdev = 0.007
  CI (99.9%): [2.294, 2.550] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.470, 2.479, 2.492), stdev = 0.012
  CI (99.9%): [2.266, 2.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.660 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
Iteration   3: 2.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.949 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.944, 2.949, 2.954), stdev = 0.005
  CI (99.9%): [2.855, 3.043] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.857 ms/op
                 createUser·p0.9999: 14.221 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 11.737 ms/op
                 createUser·p1.00:   12.026 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.939 ms/op
                 createUser·p0.999:  7.950 ms/op
                 createUser·p0.9999: 10.669 ms/op
                 createUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384928
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 189446 
    [ 2.500,  3.750) = 191299 
    [ 3.750,  5.000) = 3199 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.275 ms/op
     p(99.9900) =     13.690 ms/op
     p(99.9990) =     14.400 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.745 ms/op
                 existUser·p0.9999: 13.246 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  7.524 ms/op
                 existUser·p0.9999: 12.745 ms/op
                 existUser·p1.00:   13.287 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 12.429 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390925
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 195761 
    [ 2.500,  3.750) = 190780 
    [ 3.750,  5.000) = 3360 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      6.979 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.469 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.963 ms/op
                 getUser·p0.9999: 14.281 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  5.862 ms/op
                 getUser·p0.9999: 12.321 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  7.108 ms/op
                 getUser·p0.9999: 11.294 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385339
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 190835 
    [ 2.500,  3.750) = 190011 
    [ 3.750,  5.000) = 3725 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.114 ms/op
     p(99.9900) =     13.483 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.577 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.722 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.783 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.296 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324957
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 102054 
    [ 2.500,  3.750) = 187973 
    [ 3.750,  5.000) = 28697 
    [ 5.000,  6.250) = 4817 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     10.904 ms/op
     p(99.9990) =     11.645 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.843 ± 2.246  ops/ms
ClientPb.existUser                       thrpt       3  13.194 ± 0.415  ops/ms
ClientPb.getUser                         thrpt       3  12.908 ± 0.193  ops/ms
ClientPb.listUser                        thrpt       3  10.717 ± 1.075  ops/ms
ClientPb.createUser                       avgt       3   2.484 ± 0.624   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.213   ms/op
ClientPb.listUser                         avgt       3   2.949 ± 0.094   ms/op
ClientPb.createUser                     sample  384928   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.688           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.275           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.690           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  390925   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.979           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.812           ms/op
ClientPb.getUser                        sample  385339   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.727           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.114           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.483           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.680           ms/op
ClientPb.listUser                       sample  324957   2.951 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.818           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.904           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.731           ms/op
